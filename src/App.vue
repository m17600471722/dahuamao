
<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>
<style lang="scss">
// @import "./../lib/sass/variables.scss";
#app {
  font-size: 0.12rem;
}
html,
body,
#app {
  height: 100%;
  overflow-x: hidden;
}
</style>
<script>
//   import axios from 'axios'
//   export default {
//     created() {
//       axios.interceptors.response.use((response) => {
//         this.handleResponse(response)
//         return response
//       }, (error => {
//         this._showAlert(error)
//       }))
//     },
//     methods: {
//       handleResponse(response) {
//         // 在处理前，删除已经弹出的Alert
//         this.$store.dispatch('deleteAlert')
//         if (response.status >= 400) {
//           if (response.status === 401) {
//             this.handleUnauthorized()
//           } else if (response.status === 403) {
//             this.handleForbidden()
//           } else {
//             this.handleServerError(response)
//           }
//         } else {
//           if (response.data.status !== 0) {
//             this.handleApiError(response)
//           }
//         }
//       },
//       /**
//        * 处理服务器Http请求异常
//        * @param response
//        */
//       handleServerError(response) {
//         this._showAlert(response.statusText)
//       },
//       /**
//        * 处理服务器Http 401未登录异常
//        */
//       handleUnauthorized() {
//         this.$router.replace({name: 'login'})
//       },
//       /**
//        * 处理服务器Http 403无权限异常
//        * @param response
//        */
//       handleForbidden(response) {
//         this._showAlert(response.data.message)
//       },
//       /**
//        * 处理服务器API业务异常
//        * @param response
//        */
//       handleApiError(response) {
//         this._showAlert(response.data.message)
//       },
//       /**
//        * 向Store中分发需要弹出的消息
//        * @param message
//        * @private
//        */
//       _showAlert(message) {
//         this.$store.dispatch('createAlert', {type: 'warning', message: message})
//       }
//     }
//   }
</script>
