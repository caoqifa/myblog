<template>
  <div id="About">
    <article>
      <h2>ABOUT ME</h2>
      <p>帅气这个形容词，大概就是为我而创造的吧😏</p>
      <p>谢谢你这么好看还这么关注我鸭！我叫曹起发，你可以亲切的叫发发</p>
    </article>
    <article>
      <h2>ABOUT SITE</h2>
      <p class="code"><code>前 &nbsp;端：</code><span>Vue + Element</span></p>
      <p class="code"><code>后 &nbsp;端：</code><span>Node + Nuxt + Express + Mongodb</span></p>
      <p class="border"><code>服务器：</code><a href="https://www.aliyun.com/1111/new?userCode=xqfx5ty6" target="_blank">阿里云ECS</a></p>
      <p>这个博客我在2021上半年就开始构思了，终于在2021年上线了！我真棒！😂</p>
      <p>这不能怪我...真的...这个项目是我第一个上线的项目,所有我构思了很久,希望把我所学的都应用上去,然而能力有限,但又急于发布,所有就草草呈现给大家了😁</p>
    </article>
  </div>
</template>

<script>
export default {
  name: "About"
}
</script>

<style lang="less" scoped>

#About{
  article{
    box-sizing: border-box;
    width: 100%;
    margin-bottom: 15px;
    box-shadow: 0 0 4px #ddd;
    padding: 25px 20px;
    background-color: #fff;
    font-family: Quicksand,Microsoft YaHei,sans-serif;
    h2{
      margin-bottom: 15px;
      font-size: 20px;
      letter-spacing: 3px;
      line-height: 24px;
      border-left: 5px solid #73b899;
      text-indent: 10px;
    }
    p{
      text-indent: 2em;
      color: #444;
      font-size: 14px;
      letter-spacing: 4px;
      line-height: 30px;
      code{
        font-family: Quicksand,Microsoft YaHei,sans-serif;
        letter-spacing: 4px;
      }
      a{
        color: #409eff;
        &:hover{
          text-decoration: underline;
        }
      }
    }
    p.code span{
      color: #bd4147;
      background-color: rgba(27,31,35,.05);
      font-weight: 700;
    }
    p.border{
      border-bottom: 1px dotted rgb(170, 170, 170);
    }
  }
}

</style>














