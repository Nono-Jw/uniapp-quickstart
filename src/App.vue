<script>
export default {
  onLaunch: function() {
    console.log('App Launch');
  },
  onShow: async function() {
    console.log('App Show');
  },
  onHide: function() {
    console.log('App Hide');
  },
};
</script>

<style lang="scss">
/*每个页面公共css */
@import './uview-ui/index.scss';
@import './style/common.scss';
</style>
