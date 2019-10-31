<template>
    <div id="stopwatch">{{time}}</div>
</template>

<script>
export default {
	props: ['time']
}
</script>

<style>
#stopwatch{
  flex: 0px 1 1;
  font-size: 5rem;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>