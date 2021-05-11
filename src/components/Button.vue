<template>
    <button>
    <slot></slot>
    </button>
</template>

<script>
import { defineComponent } from 'vue';
export default defineComponent({
});
</script>

<style scoped>
button {
display: flex;
flex-direction: column;
justify-content: center;
text-align: center;
border-radius: 50px;
}

button{
background-color: white;
width: 280px;
height: 54px;
border: solid 1px white;
}
button:hover{
		filter: brightness(1.2);
	}
button:active {
		transform: scale(0.9);
	}
</style>