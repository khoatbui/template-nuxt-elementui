<template>
  <div class="custom-daterange-picker">
    <el-date-picker
      v-model="selectDate"
      type="daterange"
      range-separator="To"
      start-placeholder="Start date"
      end-placeholder="End date"
    >
    </el-date-picker>
  </div>
</template>
<script>
export default {
  name: 'CustomDateRange',
  data() {
    return {
      selectDate: ''
    }
  },
  mounted() {}
}
</script>
<style lang="postcss" scope>
.el-date-editor.el-range-editor.el-input__inner.el-date-editor--daterange {
}
.el-picker-panel.el-date-range-picker.el-popper {
  @apply tw-inline-block tw-w-screen tw-m-0 tw-p-0 tw-shadow-none tw-border-none !important;
}
.el-picker-panel__body-wrapper {
  @apply tw-w-full !important;
}
.el-picker-panel__body {
  min-width: auto !important;
  @apply tw-flex tw-flex-col tw-w-full !important;
}
.el-picker-panel__content.el-date-range-picker__content {
  @apply tw-w-full;
}
@media (min-width: 640px) {
  .el-date-editor.el-range-editor.el-input__inner.el-date-editor--daterange {
  }
  .el-picker-panel.el-date-range-picker.el-popper {
    @apply tw-inline-block tw-w-screen tw-m-0 tw-p-0 tw-shadow-none tw-border-none !important;
  }
  .el-picker-panel__body-wrapper {
    @apply tw-w-full !important;
  }
  .el-picker-panel__body {
    min-width: auto !important;
    @apply tw-flex tw-flex-col tw-w-full !important;
  }
  .el-picker-panel__content.el-date-range-picker__content {
    @apply tw-w-full;
  }
}
@media (min-width: 768px) {
  .el-date-editor.el-range-editor.el-input__inner.el-date-editor--daterange {
  }
  .el-picker-panel.el-date-range-picker.el-popper {
    @apply tw-inline-block tw-w-screen tw-m-0 tw-p-0 tw-shadow-none tw-border-none !important;
  }
  .el-picker-panel__body-wrapper {
    @apply tw-w-full !important;
  }
  .el-picker-panel__body {
    min-width: auto !important;
    @apply tw-flex tw-flex-col tw-w-full !important;
  }
  .el-picker-panel__content.el-date-range-picker__content {
    @apply tw-w-full;
  }
}
@media (min-width: 1024px) {
}
@media (min-width: 1280px) {
}
</style>
