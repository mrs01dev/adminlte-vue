<template>
  <a-chart-js :id="id_local" :type="getType()" :labels="labels_local" :options="options_local" :datasets="datasets_local"/>
</template>
<script>
import ChartJsContainer from '../AChartJs/ChartJsContainer'

export default {
  name: 'AChartJsPie',
  extends: ChartJsContainer,
  props: {
    id: { type: String, default: 'chart_pie_' + Math.floor(Math.random() * 1000) }
  },
  methods: {
    getType () {
      return 'pie'
    }
  }
}
</script>
