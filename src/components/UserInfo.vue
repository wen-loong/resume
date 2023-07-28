<template>
  <div class="profile">
    <el-row :gutter="20">
      <el-col :span="16">
        <div class="basic-info">
          <el-row>
            <el-col :span="8">
              <div class="name"><h2>环文龙</h2></div>
            </el-col>
            <el-col :span="8">
              <div class="infos">
                <div class="mobile">
                  <a href="tel: 17721348451"><span>17721348451</span> </a>
                </div>
                <div class="email">
                  <a href="mailto: huan.wenlong.529@gmail.com">
                    <span>huan.wenlong.529@gmail.com</span>
                  </a>
                </div>
                <div class="github">
                  <a href="https://github.com/wen-loong">
                    <span>https://github.com/wen-loong </span>
                  </a>
                </div>
                <div class="website">
                  <a href="https://wen-loong.github.io/">
                    <span>https://wen-loong.github.io/</span>
                  </a>
                </div>
              </div>
            </el-col>
          </el-row>
        </div>
      </el-col>
      <el-col :span="8">
        <div class="avatar">
          <el-avatar shape="square" :size="100" :src="avatar" />
        </div>
      </el-col>
    </el-row>
  </div>
</template>

<script lang="ts">
import avatar from '../assets/avatar.jpg'
export default {
  data() {
    return {
      avatar: avatar
    }
  }
}
</script>

<style scoped>
.profile {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap-reverse;
  margin-bottom: 12px;
}
.infos {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap-reverse;
  margin-bottom: 12px;
}
/* .el-row {
  margin-bottom: 20px;
}
.el-row:last-child {
  margin-bottom: 0;
}
.el-col {
  border-radius: 4px;
}

.grid-content {
  border-radius: 4px;
  min-height: 36px;
} */
</style>
