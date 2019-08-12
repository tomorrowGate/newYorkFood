<template>
  <div>
    <mt-tabbar v-model="selected">
        <mt-tab-item id="外卖">
            <img slot="icon" src="">
            外卖
        </mt-tab-item>
        <mt-tab-item id="订单">
            <img slot="icon" src="">
            订单
        </mt-tab-item>
        <mt-tab-item id="发现">
            <img slot="icon" src="">
            发现
        </mt-tab-item>
        <mt-tab-item id="我的">
            <img slot="icon" src="">
            我的
        </mt-tab-item>
    </mt-tabbar>


    <!-- <mt-tab-container v-model="active">
      <mt-tab-container-item id="tab-container1">
        <mt-cell v-for="n in 10" title="tab-container 1" :key="n"></mt-cell>
      </mt-tab-container-item>
      <mt-tab-container-item id="tab-container2">
        <mt-cell v-for="n in 5" title="tab-container 2" :key="n"></mt-cell>
      </mt-tab-container-item>
      <mt-tab-container-item id="tab-container3">
        <mt-cell v-for="n in 7" title="tab-container 3" :key="n"></mt-cell>
      </mt-tab-container-item>
    </mt-tab-container> -->
  </div>
</template>

<script>

export default {
  name: 'Tabbar',

  data () {
    return {
    }
  },

  methods: {}
}
</script>

<style >

</style>

