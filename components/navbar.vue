<template>
    <div id="nav">
        <button>
            <NuxtLink style="" to="/">Home
            </NuxtLink>
        </button><button>
            <NuxtLink to="/projects">"Projects" </NuxtLink>
        </button>
    </div>
</template>
<script></script>
<style>
#nav {

    float: left;
    padding: 15px;
}

* {
    text-decoration: none;
    color: inherit;
}

button {
    border-radius: 12px;
    font-size: 25px;
    margin-right: 10px;
    border-style: solid;
    border-color: #5e81ac;
    color: #5e81ac;
    background-color: #2e3440;
}

button:hover {
    color: #ebcb8b;
    border-color: #ebcb8b;
    transition: 500ms;
}</style>