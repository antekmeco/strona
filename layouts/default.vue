<template>
    <navbar />
    <div id="content">
        <slot />
    </div>
</template>
<style>
#content {
  margin: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
}
</style>