<script>
import { h } from 'vue'
export default (_, { slots }) => h('div', { class: 'test' }, 'Hello with a render function');

</script>

<style lang="postcss" scoped>
.test {
  color: red;
}
</style>
