<template>
  <div class="index">
    <div class="top">
      <!-- <el-menu :ellipsis=false class="el-menu-demo" mode="horizontal" background-color="black" text-color="#fff"
        active-text-color="#ffd04b">
        <el-menu-item index="1-1" @click="shouye">首页</el-menu-item>
        <el-menu-item index="1-2" @click="ymbhp">关于成理</el-menu-item>
        <el-menu-item index="1-3" @click="join">加入我们</el-menu-item>
        <el-menu-item index="1-4" @click="guanyuwomen">关于我们</el-menu-item>
      </el-menu> -->
      <!-- <el-menu :ellipsis=false :default-active="activeIndex2" class="el-menu-demo" mode="horizontal"
        background-color="black" text-color="#fff" active-text-color="#ffd04b" @select="handleSelect">
        <el-menu-item index="1-1" @click="shouye">首页</el-menu-item>
        <el-menu-item index="1-2" @click="ymbhp">关于成理</el-menu-item>
        <el-menu-item index="1-3" @click="join">加入我们</el-menu-item>
        <el-menu-item index="1-4" @click="guanyuwomen">关于我们</el-menu-item>

      </el-menu> -->
    </div>

    <div class="content1">
      <div class="left_title">
        <span class="title">ITA</span>
        <span class="title"> 成理 最吊的 计算机社团 </span>
        <span class="content">加入我们 </span>
        <span class="content">创造未来</span>
        <div class="first-stack-links">
          <a href="#" class="about-button" @click="scrollSmooth">下滑查看更多 ↓</a>
        </div>
      </div>
      <a href="#" class="about-img">
        <img class="jpg" src="C:\Users\苏九\Desktop\code\图片\32FE051CD51432A610DD3CDCD35376D5.jpg" alt="此处应该有图片">
      </a>
    </div>
    <div class="content2">
      <span>"欧里给！！"</span>
      <img class="content2-img" src="C:\Users\苏九\Desktop\code\图片\32FE051CD51432A610DD3CDCD35376D5.jpg" alt="">
      <span>sujiu</span>
      <span class="group-description" style="font-size: 15px;">欧里给给给给！！！！！</span>
    </div>
    <div class="product-group" id="以前团队" style=" margin-top: 100px;">
      <h2 class="group-title">社团简介 </h2>
      <span class="group-description">为什么加入我们</span>
      <div class="group-items" style="justify-content: center; align-items: center; text-align: center;">
        <div class="content3">
          <div class="text-content">
            &nbsp;&nbsp;&nbsp;&nbsp;我们是成都理工大学宜宾校区的学术型社团，我们希望构建一个专业、开放、互助的计算机各领域的学习平台，专注于计算机科学及其相关领域的探索与实践。无论你是游戏开发的爱好者，还是对前端、算法、后端、嵌入式技术有浓厚兴趣，你都能在这里学习到相关的知识，找到志同道合的伙伴！欢迎大家加入我们这个温暖的大家庭！
          </div>


        </div>



      </div>
    </div>





    <div class="product-group" id="团队" ref="productGroup" style=" margin-left: 12%;">
      <h2 class="group-title">专业团队 </h2>
      <span class="group-description">现在ITA前线成员</span>
      <div class="group-items">
        <div class="group-item">
          <a href="#" class="group-item-icon">
            <img class="group-item-icon-img" src="../pho/b_b131f4195a618916d4731d5995e0380b.jpg" alt="头像">
          </a>
          <div class="group-info">
            <div class="group-info-intro">
              <div class="group-info-div">
                <a href="#" class="group-info-name">
                  日常の退廃……
                  <sup class="suppp-red">会长</sup>
                </a>
                <a href="#" class="group-info-discript">
                  23级现任会长
                </a>
                <div class="group-info-button">
                  <a href="" class="linkbutton-blue">博客</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="group-item">
          <a href="#" class="group-item-icon">
            <img class="group-item-icon-img"
              src="C:\Users\苏九\Desktop\code\c\c\src\pho\b_e8080010be88045de4a3aa6b037c6bab.jpg" alt="头像">
          </a>
          <div class="group-info">
            <div class="group-info-intro">
              <div class="group-info-div">
                <a href="#" class="group-info-name">
                  997283

                  <sup class="suppp-blue">副会长</sup>
                </a>
                <a href="#" class="group-info-discript">
                  23级现任副会长
                </a>
                <div class="group-info-button">
                  <a href="" class="linkbutton-blue">博客</a>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="group-item">
          <a href="#" class="group-item-icon">
            <img class="group-item-icon-img" src="../pho/buer.jpg" alt="头像">
          </a>
          <div class="group-info">
            <div class="group-info-intro">
              <div class="group-info-div">
                <a href="#" class="group-info-name">
                  不二
                  <sup class="suppp-blue">副会长</sup>
                </a>
                <a href="#" class="group-info-discript">
                  23级副现任会长
                </a>
                <div class="group-info-button">
                  <a href="" class="linkbutton-blue">博客</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="group-item">
          <a href="#" class="group-item-icon">
            <img class="group-item-icon-img" src="../pho/pharaoh.jpg" alt="头像">

          </a>
          <div class="group-info">
            <div class="group-info-intro">
              <div class="group-info-div">
                <a href="#" class="group-info-name">
                  pharaoh
                  <sup class="suppp-blue">部长</sup>
                </a>
                <a href="#" class="group-info-discript">
                  23级现任执行部部长
                </a>
                <div class="group-info-button">
                  <a href="" class="linkbutton-blue">博客</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="group-item">
          <a href="#" class="group-item-icon">
            <img class="group-item-icon-img" src="../pho/intmian.jpg" alt="头像">
          </a>
          <div class="group-info">
            <div class="group-info-intro">
              <div class="group-info-div">
                <a href="#" class="group-info-name">
                  int mian【】
                  <sup class="suppp-blue">部长</sup>
                </a>
                <a href="#" class="group-info-discript">
                  23级现任竞赛部部长
                </a>
                <div class="group-info-button">
                  <a href="" class="linkbutton-blue">博客</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="group-item">
          <a href="#" class="group-item-icon">
            <img class="group-item-icon-img" src="../pho/yuxing.jpg" alt="头像">
          </a>
          <div class="group-info">
            <div class="group-info-intro">
              <div class="group-info-div">
                <a href="#" class="group-info-name">
                  踽行

                  <sup class="suppp-blue">部长</sup>
                </a>
                <a href="#" class="group-info-discript">
                  23级现任综学部部长
                </a>
                <div class="group-info-button">
                  <a href="" class="linkbutton-blue">博客</a>
                </div>
              </div>
            </div>
          </div>
        </div>



      </div>
    </div>
    <!-- <div class="product-group" id="以前团队" style=" margin-top: 100px;">
      <h2 class="group-title">专业团队 </h2>
      <span class="group-description">现在ITA前线成员</span>
      <div class="group-items">
        <div class="group-item">
          <a href="#" class="group-item-icon">
            <img class="group-item-icon-img" src="C:\Users\苏九\Desktop\code\图片\ECCD675388067A57F2B0BC1BAD0FCB72.jpg"
              alt="头像">
          </a>
          <div class="group-info">
            <div class="group-info-intro">
              <div class="group-info-div">
                <a href="#" class="group-info-name">
                  苏九
                  <sup class="suppp-blue">会长</sup>
                </a>
                <a href="#" class="group-info-discript">
                  23级现任会长
                </a>
                <div class="group-info-button">
                  <a href="" class="linkbutton-blue">博客</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="group-item">
          <a href="#" class="group-item-icon">
            <img class="group-item-icon-img" src="C:\Users\苏九\Desktop\code\图片\ECCD675388067A57F2B0BC1BAD0FCB72.jpg"
              alt="头像">
          </a>
          <div class="group-info">
            <div class="group-info-intro">
              <div class="group-info-div">
                <a href="#" class="group-info-name">
                  苏九
                  <sup class="suppp-blue">会长</sup>
                </a>
                <a href="#" class="group-info-discript">
                  23级现任会长
                </a>
                <div class="group-info-button">
                  <a href="" class="linkbutton-blue">博客</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="group-item">
          <a href="#" class="group-item-icon">
            <img class="group-item-icon-img" src="C:\Users\苏九\Desktop\code\图片\ECCD675388067A57F2B0BC1BAD0FCB72.jpg"
              alt="头像">
          </a>
          <div class="group-info">
            <div class="group-info-intro">
              <div class="group-info-div">
                <a href="#" class="group-info-name">
                  苏九
                  <sup class="suppp-blue">会长</sup>
                </a>
                <a href="#" class="group-info-discript">
                  23级现任会长
                </a>
                <div class="group-info-button">
                  <a href="" class="linkbutton-blue">博客</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="group-item">
          <a href="#" class="group-item-icon">
            <img class="group-item-icon-img" src="C:\Users\苏九\Desktop\code\图片\ECCD675388067A57F2B0BC1BAD0FCB72.jpg"
              alt="头像">
          </a>
          <div class="group-info">
            <div class="group-info-intro">
              <div class="group-info-div">
                <a href="#" class="group-info-name">
                  苏九
                  <sup class="suppp-blue">会长</sup>
                </a>
                <a href="#" class="group-info-discript">
                  23级现任会长
                </a>
                <div class="group-info-button">
                  <a href="" class="linkbutton-blue">博客</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="group-item">
          <a href="#" class="group-item-icon">
            <img class="group-item-icon-img" src="C:\Users\苏九\Desktop\code\图片\ECCD675388067A57F2B0BC1BAD0FCB72.jpg"
              alt="头像">
          </a>
          <div class="group-info">
            <div class="group-info-intro">
              <div class="group-info-div">
                <a href="#" class="group-info-name">
                  苏九
                  <sup class="suppp-blue">会长</sup>
                </a>
                <a href="#" class="group-info-discript">
                  23级现任会长
                </a>
                <div class="group-info-button">
                  <a href="" class="linkbutton-blue">博客</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="group-item">
          <a href="#" class="group-item-icon">
            <img class="group-item-icon-img" src="C:\Users\苏九\Desktop\code\图片\ECCD675388067A57F2B0BC1BAD0FCB72.jpg"
              alt="头像">
          </a>
          <div class="group-info">
            <div class="group-info-intro">
              <div class="group-info-div">
                <a href="#" class="group-info-name">
                  苏九
                  <sup class="suppp-blue">副会长</sup>
                </a>
                <a href="#" class="group-info-discript">
                  23级现任会长
                </a>
                <div class="group-info-button">
                  <a href="" class="linkbutton-blue">博客</a>
                </div>
              </div>
            </div>
          </div>
        </div>



      </div>
    </div> -->
  </div>
</template>

<script setup>

import { ref } from 'vue'
import { useRouter } from 'vue-router';
const productGroup = ref(null);
const activeIndex = ref('1');
const router = useRouter();


const guanyuwomen = () => {
  router.push('/Intro');
}
const shouye = () => {
  router.push('/#');
}

const join = () => {
  window.open(`https://qm.qq.com/q/9tPRlHXADS `, '_blank');
}
const scrollSmooth = () => {
  productGroup.value.scrollIntoView({ behavior: 'smooth' });
}

const ymbhp = () => {
  window.open('https://cdut.ymbhp.com/ ', '_blank');
}

</script>

<style lang="scss" scoped>
.index {
  width: 100%;
  max-width: 100vw;
  /* 限制最大宽度 */
  overflow-x: hidden;
  /* 防止水平滚动 */
  background: #eef0f0;
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100%;
  /* 确保宽度自适应 */
  max-width: 100vw;
  /* 限制最大宽度 */
  overflow-x: hidden;
  /* 隐藏水平溢出 */

  .top {
    display: flex;
    width: 100%;
    justify-content: flex-end;
    background-color: black;

    .el-menu--horizontal {
      border-bottom: none;
    }
  }

  .content1 {
    display: flex;
    justify-content: space-between;
    margin-top: 180px;
    margin-bottom: 120px;
    align-items: center;

    .left_title {


      line-height: 75px;
      font-weight: bold;
      font-family: system-ui;
      color: #00001e;
      display: flex;
      flex-direction: column;
      font-size: 70px;
      font-weight: 400;

      .content {
        font-size: 30px;
        line-height: 30px;
      }

      .first-stack-links {
        display: flex;

        .about-button {
          text-decoration: none;
          display: flex;
          padding: 0 36px;
          background: black;
          color: white;
          font-size: 20px;
          border-radius: 29px;
          box-shadow: 0px 12px 12px -9px rgba(0, 0, 0, 0.29);
          margin-top: 64px;
          width: fit-content;
          transition: ease-in-out 0.3s;
          white-space: nowrap;
          align-items: center;
          justify-content: center;
          width: 200px;
          height: 48px;
        }
      }
    }

    a {

      /* 保证 a 标签大小不会受 flex 影响 */
      .jpg {
        width: 405px;
        max-width: 100%;
        animation: floating 4s ease-in-out infinite;
        pointer-events: none;
        object-fit: cover;
        transform: translate(0, -7px);
        border-radius: 10%;
        margin-left: 40px;
      }
    }
  }

  @keyframes floating {
    0% {
      transform: translate(0, 0px);
    }

    50% {
      transform: translate(0, 10px);
    }

    100% {
      transform: translate(0, 0px);
    }
  }
}

div.product-group {

  justify-content: center;
  min-width: 1186.44px;
  /* 设置固定的最小高度 */
  height: auto;
  display: flex;
  flex-direction: column;
}

h2.group-title {
  font-size: 30px;
  text-align: left;
}

div.content3 {
  // display: flex;
  // flex-direction: column;
  // padding: 24px 32px;
  // background: white;
  // margin: 0 5%;
  // border-radius: 12px;
  // line-height: 1.5;
  // max-width: 1200px;
  // width: 750px;
  // height: 200px;
  // margin-top: 18px;
  // border: 1px solid #e6e6ec;
  // align-content: center;
  // align-items: center;
  // box-shadow: 2px #e6e6ec;

  display: flex;
  flex-direction: row;
  text-align: center;
  align-items: center;
  padding: auto;
  justify-content: center;
  /* 水平居中 */
  align-items: center;
  /* 垂直居中 */
  text-align: center;
}

div.text-content {

  font-size: 21px;
  display: flex;
  flex-direction: column;
  padding: 24px 32px;
  background: white;
  margin: 0 5%;
  text-align: left;
  border-radius: 12px;
  line-height: 1.5;
  max-width: 1200px;
  width: 950px;
  height: 200px;
  margin-top: 18px;
  border: 1px solid #e6e6ec;
  align-content: center;
  align-items: center;
  box-shadow: 2px 2px 5px #c4c4cd;
}

div.content2 {
  // display: flex;
  // background: white;
  // flex-direction: column;
  // max-width: 1200px;
  // margin-top: 18px;
  // padding: 24px 32px
  display: flex;
  flex-direction: column;

  padding: 24px 32px;
  background: white;
  margin: 0 5%;
  border-radius: 12px;
  line-height: 1.5;
  max-width: 1200px;
  width: 500px;
  height: 200px;
  margin-top: 18px;
  border: 1px solid #e6e6ec;
  align-content: center;
  align-items: center;
  box-shadow: 2px #e6e6ec;
}

span.group-description {
  color: grey;
}

div.group-items {

  display: flex;
  flex-direction: row;
  justify-items: space-between;
  padding-top: 50px;
  flex-wrap: wrap;
}

div.group-item {

  display: flex;
  margin-bottom: 60px;
  flex-direction: row;
  display: flex;
  width: calc(100% / 3);
  margin-bottom: 60px;
}

img.group-item-icon-img {
  height: 100px;
  width: 100px;
  border-radius: 28px;
}

div.group-info {
  display: flex;
  flex-direction: column;
  margin-left: 20px;
  align-items: center;
  justify-content: left;
}

h3.group-item-title {
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 8px;
}

p.group-item-description {
  font-size: 16px;
  color: grey;
  margin-bottom: 8px;
}

a.group-item-link {
  font-size: 16px;
  color: #007bff;
  text-decoration: none;
}



div.group-info-intro {
  display: flex;
  flex-direction: column;

}

a.group-info-name {
  text-decoration: none;
  color: black;
  font-size: 23px;


}

.suppp-red {
  font-size: 12px;
  background: red;
  color: white;
  padding: 4px;
  border-radius: 4px;
  margin-left: 6px;
  white-space: nowrap;
  position: absolute;
  position: relative;
  width: 30px;
  height: 18px;
}

.suppp-blue {
  font-size: 12px;
  background: blue;
  color: white;
  padding: 4px;
  border-radius: 4px;
  margin-left: 6px;
  white-space: nowrap;
  position: absolute;
  position: relative;
  width: 30px;
  height: 18px;
}

a.group-info-discript {
  font-size: 14px;
  color: black;
  text-decoration: none;

}

div.group-info-div {
  display: flex;
  flex-direction: column;
}

div.group-info-button {
  margin-top: 12px;
  display: flex;
  align-items: center;
}

a.linkbutton-grey {
  padding: 6px 20px;
  display: flex;
  background: grey;
  color: white;
  font-size: 14px;
  border-radius: 21px;
  //transition: ease-in-out 0.3s;
  width: fit-content;
  white-space: nowrap;
  text-decoration: none;
}

a.linkbutton-blue {

  text-decoration: none;
  padding: 6px 20px;
  display: flex;
  background: blue;
  color: white;
  font-size: 14px;
  border-radius: 21px;
  //transition: ease-in-out 0.3s;
  width: fit-content;
  white-space: nowrap;

}

// .index {
//   cursor: url('../assets/normal.cur'), auto;
// }

img.content2-img {
  margin-top: 30px;
  width: 60px;
  height: auto;
  object-fit: contain;
  border-radius: 50%;
  /* 或者使用 cover */
}

@media (max-width: 600px) {

  .content1 {
    flex-direction: column;
    align-items: center;
  }

  div.text-content {
    width: 350px;
    font-size: 13px;
  }

  div.content2 {
    width: 400px;
    height: auto;
  }

  .left_title {
    font-size: 2rem;
    /* 调整字体大小 */
    text-align: center;
    /* 居中对齐 */
  }

  div.group-items {
    flex-direction: column;
  }



  img.jpg {
    width: 300px;
    height: auto;
    /* 保证图片缩放比例 */
    margin: 10px 0;
    /* 增加上下间距 */
  }

  .about-button {
    margin: auto;
    width: 100%;
    font-size: 1rem;
    /* 调整按钮字体大小 */
  }

  .group-items {
    align-items: center;
    /* 居中对齐 */
  }

  .group-item {
    width: 100%;
    /* 占满整行 */
    margin-bottom: 20px;
    display: flex;
    flex-direction: column;
    /* 垂直排列 */
    align-items: center;
  }

  .group-item-icon-img {
    width: 80px;
    /* 调整头像大小 */
    height: 80px;
    border-radius: 50%;
    /* 圆形头像 */
  }

  .group-info {
    text-align: center;

    /* 信息居中 */
  }

  .about-button {
    width: 100%;
    /* 按钮自适应宽度 */
    padding: 10px;
    /* 内边距调整 */
    font-size: 1rem;
    /* 调整字体大小 */
  }

  .index .content1 a .jpg {
    width: 300px;
    height: auto;
    margin: 10px 0;
  }

}
</style>
