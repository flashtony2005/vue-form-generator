<template lang="jade">
	input.form-control(type="email", v-model="value", :readonly="schema.readonly", :disabled="disabled", :placeholder="schema.placeholder")
</template>

<script>
	import abstractField from "./abstractField";
	export default {
		mixins: [ abstractField ]
	};
</script>


<style lang="sass" scoped>
	input {
		width: 100%;
	}
</style>
