<script lang="tsx">
  import { defineComponent } from 'compatible-vue';

  export default defineComponent({
    name: 'AuthTest1',
    setup() {
      return () => (
        <div class="p-4">
          admin角色可见
          <input />
        </div>
      );
    },
  });
</script>
