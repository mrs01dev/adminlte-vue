<template>
  <BCard class="card-primary">
    <template slot="header">
      <h3 class="card-title">{{title}}</h3>
      <div class="card-tools">
        <button type="button" class="btn btn-tool" data-card-widget="remove"><i class="fas fa-times"></i>
        </button>
      </div>
    </template>
    <slot name="body">{{body}}</slot>
  </BCard>
</template>
<script>
export default {
  name: 'ACardRemovable',
  data () { return { } },
  props: {
    title: { type: String },
    body: { type: String }
  }
}
</script>
