<template>

</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class Card extends Vue {
  @Prop() private msg!: string;
}
</script>

<style scoped lang="sass">

</style>
