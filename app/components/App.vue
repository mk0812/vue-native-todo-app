<template>
	<page>
		<action-bar title="Todoリスト"></action-bar>
		<todo></todo>
	</page>
</template>

<script>
import Todo from './Todo.vue'
export default {
	components: {
		Todo
	}
}
</script>

<style scoped>
    label {
        text-align: center;
        font-size: 25;
    }

    Button {
        background-color: #00caab;
    }
</style>