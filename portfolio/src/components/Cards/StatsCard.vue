<template>
  <md-card class="md-card-stats">
    <md-card-header :data-background-color="dataBackgroundColor">
      <slot name="header" />
    </md-card-header>

    <md-card-content>
      <slot name="content" />
    </md-card-content>

    <md-card-actions md-alignment="left">
      <slot name="footer" />
    </md-card-actions>
  </md-card>
</template>
<script>
export default {
  name: "StatsCard",
  props: {
    dataBackgroundColor: {
      type: String,
      default: ""
    }
  }
};
</script>
