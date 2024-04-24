<!--
<script setup>
import { reactive, ref } from 'vue'

const counter = reactive({ count: 0 })
const message = ref('Hello World!')
</script>

<template>
  <h1>{{ message }}</h1>
  <p>Count is: {{ counter.count }}</p>
</template>
-->


<!--
<script setup>
import { reactive, ref } from 'vue'

const titleClass = ref('title')
</script>

<template>
  
  <h1 :class="titleClass">Make me red</h1>
</template>

<style>
.title {
  color: red;
}
</style>
-->


<!--
<script setup>
import { ref } from 'vue'

const count = ref(0)

function increment(){
        count.value++
    }
    </script>    

<template>
  <button v-on:click="increment">{{ count }}</button>
</template>
-->


<!--
<script setup>
import { ref } from 'vue'

const text = ref('')

    function onInput(e){
        text.value = e.target.value
    }
</script>

<template>
  <input v-model="text" placeholder="Type here">
  <p>{{ text }}</p>
</template>
-->


<!--
<script setup>
import { ref } from 'vue'

const awesome = ref(true)

function toggle() {
  awesome.value = !awesome.value
}
</script>

<template>
  <button @click="toggle">toggle</button>
  <h1 v-if="awesome">Vue is awesome!</h1>
  <h1 v-else>Oh no 😢</h1>
</template>
-->
