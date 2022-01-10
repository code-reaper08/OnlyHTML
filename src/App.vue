<template>
  <router-view />
</template>

<style>
/* Universal styles here */
:root {
  --main-bg-color: #282828;
  --primary-text-color: #33ff00;
  --secondary-text-color: #000000;
  --ternary-text-color: #66ff66;
  --subtitle-text-color: #ffffff;
  --button-bg-color: #ffb000;
}
#app {
  /* height: 100vh; */
  background-color: var(--main-bg-color);
  font-family: "Source Code Pro", monospace;
}
button {
  background-color: var(--button-bg-color);
  outline: none;
  border: none;
  padding: 0.5rem;
}
button:focus {
  border: var(--subtitle-text-color);
}
a {
  color: var(--button-bg-color);
  text-decoration: none;
}
a:focus {
  border: var(--subtitle-text-color);
}
* {
  margin: 0;
  padding: 0;
}
</style>
