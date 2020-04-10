<template>
  <div class="test-container">
    主题一<xp-checkbox v-model="checked1" theme="theme1">方案1 </xp-checkbox>
    <xp-checkbox v-model="checked2" theme="theme1">方案2</xp-checkbox>
    <br />
    <br />
    第1个传回来的值{{ checked1 }} 第2个传回来的值{{ checked2 }}
    <br />
    <br />
    主题二<xp-checkbox v-model="checked3" theme="theme2">方案3 </xp-checkbox>
    <xp-checkbox v-model="checked4" theme="theme2">方案4</xp-checkbox>
    <br />
    <br />
    第3个传回来的值{{ checked3 }} 第4个传回来的值{{ checked4 }}
    <br />
    <br />
    主题三<xp-checkbox v-model="checked5" theme="theme3">方案5 </xp-checkbox>
    <xp-checkbox v-model="checked6" theme="theme3">方案6</xp-checkbox>
    <br />
    <br />
    第5个传回来的值{{ checked5 }} 第6个传回来的值{{ checked6 }}
  </div>
</template>
<script>
import XpCheckbox from "@/components/XpCheckbox";

export default {
  components: { XpCheckbox },
  data() {
    return {
      checked1: true,
      checked2: false,
      checked3: true,
      checked4: false,
      checked5: true,
      checked6: false,
    };
  },
  methods: {},
};
</script>
