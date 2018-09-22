<template>
  <div id="designer">
    <H1>拖拽设计器-基于canvas-V1.0</H1>

    <div class="pitch">
      <div class="pick">
        <span>选择你的设计类型</span>
      </div>
      <ul class="choices">
        <li class="choice">
          <div class="image">
            <router-link :to="{path:'/diagram/' + type + '/15'}">
              <template v-if="type === 'coach'">
                <svg xmlns="http://www.w3.org/2000/svg" width="308" height="308" viewBox="0 0 370.75 370.75"><title>
                  <!-- react-text: 534 -->Asset 32<!-- /react-text --></title>
                  <g id="Layer_2" data-name="Layer 2">
                    <g id="TCM">
                      <rect x="1" y="1" width="368.75" height="368.75"
                            style="fill: rgb(255, 255, 255); stroke: rgb(213, 213, 213); stroke-width: 5px;"></rect>
                    </g>
                  </g>
                </svg>
              </template>
              <template v-else>
                <svg xmlns="http://www.w3.org/2000/svg" width="308" height="308" viewBox="0 0 370.75 370.75"><title>
                  <!-- react-text: 721 -->Asset 31<!-- /react-text --></title>
                  <g id="Layer_2" data-name="Layer 2">
                    <g id="USSF">
                      <rect x="171.14" y="-168.46" width="28.47" height="368.75"
                            transform="translate(201.29 -169.46) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="171.14" y="-139.99" width="28.47" height="368.75"
                            transform="translate(229.76 -140.99) rotate(90)" style="fill: rgb(166, 206, 147);"></rect>
                      <rect x="171.14" y="-111.52" width="28.47" height="368.75"
                            transform="translate(258.23 -112.52) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="171.14" y="-83.05" width="28.47" height="368.75"
                            transform="translate(286.7 -84.05) rotate(90)" style="fill: rgb(166, 206, 147);"></rect>
                      <rect x="171.14" y="-54.58" width="28.47" height="368.75"
                            transform="translate(315.17 -55.58) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="171.14" y="-26.11" width="28.47" height="368.75"
                            transform="translate(343.64 -27.11) rotate(90)" style="fill: rgb(166, 206, 147);"></rect>
                      <rect x="171.14" y="2.02" width="28.47" height="368.75"
                            transform="translate(371.77 1.02) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="171.14" y="30.49" width="28.47" height="368.75"
                            transform="translate(400.24 29.49) rotate(90)" style="fill: rgb(166, 206, 147);"></rect>
                      <rect x="171.14" y="58.36" width="28.47" height="368.75"
                            transform="translate(428.11 57.36) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="171.14" y="86.83" width="28.47" height="368.75"
                            transform="translate(456.58 85.83) rotate(90)" style="fill: rgb(166, 206, 147);"></rect>
                      <rect x="171.14" y="115.56" width="28.47" height="368.75"
                            transform="translate(485.31 114.56) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="171.14" y="144.03" width="28.47" height="368.75"
                            transform="translate(513.78 143.03) rotate(90)" style="fill: rgb(166, 206, 147);"></rect>
                      <rect x="171.82" y="171.82" width="27.11" height="368.75"
                            transform="translate(541.57 170.82) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="1" y="1" width="368.75" height="368.75"
                            style="fill: none; stroke: rgb(255, 255, 255); stroke-width: 5px;"></rect>
                    </g>
                  </g>
                </svg>
              </template>
            </router-link>
          </div>
          <div class="text">
            转换设计器-transform-ktr
          </div>
        </li>
        <li class="choice">
          <div class="image">
            <router-link :to="{path:'/diagram/' + type + '/15'}">
              <template v-if="type === 'coach'">
                <svg xmlns="http://www.w3.org/2000/svg" width="308" height="308" viewBox="0 0 370.75 370.75"><title>
                  <!-- react-text: 534 -->Asset 32<!-- /react-text --></title>
                  <g id="Layer_2" data-name="Layer 2">
                    <g id="TCM">
                      <rect x="1" y="1" width="368.75" height="368.75"
                            style="fill: rgb(255, 255, 255); stroke: rgb(213, 213, 213); stroke-width: 5px;"></rect>
                    </g>
                  </g>
                </svg>
              </template>
              <template v-else>
                <svg xmlns="http://www.w3.org/2000/svg" width="308" height="308" viewBox="0 0 370.75 370.75"><title>
                  <!-- react-text: 721 -->Asset 31<!-- /react-text --></title>
                  <g id="Layer_2" data-name="Layer 2">
                    <g id="USSF">
                      <rect x="171.14" y="-168.46" width="28.47" height="368.75"
                            transform="translate(201.29 -169.46) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="171.14" y="-139.99" width="28.47" height="368.75"
                            transform="translate(229.76 -140.99) rotate(90)" style="fill: rgb(166, 206, 147);"></rect>
                      <rect x="171.14" y="-111.52" width="28.47" height="368.75"
                            transform="translate(258.23 -112.52) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="171.14" y="-83.05" width="28.47" height="368.75"
                            transform="translate(286.7 -84.05) rotate(90)" style="fill: rgb(166, 206, 147);"></rect>
                      <rect x="171.14" y="-54.58" width="28.47" height="368.75"
                            transform="translate(315.17 -55.58) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="171.14" y="-26.11" width="28.47" height="368.75"
                            transform="translate(343.64 -27.11) rotate(90)" style="fill: rgb(166, 206, 147);"></rect>
                      <rect x="171.14" y="2.02" width="28.47" height="368.75"
                            transform="translate(371.77 1.02) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="171.14" y="30.49" width="28.47" height="368.75"
                            transform="translate(400.24 29.49) rotate(90)" style="fill: rgb(166, 206, 147);"></rect>
                      <rect x="171.14" y="58.36" width="28.47" height="368.75"
                            transform="translate(428.11 57.36) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="171.14" y="86.83" width="28.47" height="368.75"
                            transform="translate(456.58 85.83) rotate(90)" style="fill: rgb(166, 206, 147);"></rect>
                      <rect x="171.14" y="115.56" width="28.47" height="368.75"
                            transform="translate(485.31 114.56) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="171.14" y="144.03" width="28.47" height="368.75"
                            transform="translate(513.78 143.03) rotate(90)" style="fill: rgb(166, 206, 147);"></rect>
                      <rect x="171.82" y="171.82" width="27.11" height="368.75"
                            transform="translate(541.57 170.82) rotate(90)" style="fill: rgb(129, 190, 111);"></rect>
                      <rect x="1" y="1" width="368.75" height="368.75"
                            style="fill: none; stroke: rgb(255, 255, 255); stroke-width: 5px;"></rect>
                    </g>
                  </g>
                </svg>
              </template>
            </router-link>
          </div>
          <div class="text">
            作业设计器-job-kjb
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'designer',
    components: {},
    data() {
      return {}
    },
    computed: {
      type() {
        return this.$route.params.type;
      }
    },
    mounted() {
      let imageDivs = document.getElementsByClassName('image');
      if (this.type === 'coach') {
        for (let imageDiv of imageDivs) {
          imageDiv.style.backgroundImage = 'url(/static/img/pitchBg1.png)';
        }
      } else if (this.type === 'standard') {
        for (let imageDiv of imageDivs) {
          imageDiv.style.backgroundImage = 'url(/static/img/pitchBg2.png)';
        }
      }
    }
  }
</script>

<style lang="scss" scoped>
  html, body {
    width: 100%;
    height: 100%;
  }

  .pitch {
    width: 100%;
    height: 100%;
    background-color: rgb(67, 69, 79);
    .header {
      width: 100%;
    }
    .pick {
      width: 100%;
      height: 40px;
      text-align: center;
      color: white;
      font-size: 25px;
      font-weight: 500;
      margin: 50px auto 30px auto;
    }
    .choices {
      width: 100%;
      display: flex;
      flex-flow: wrap;
      list-style: none;
      background-color: rgb(67, 69, 79);
      .choice {
        width: 45%;
        height: 400px;
        text-align: center;
        margin: 0 15px 30px 15px;
        border-radius: 4px;
        transition: all 0.2s;
        background-color: white;
        &:hover {
          transform: scale(1.03);
        }
        .image {
          padding: 10px 0;
          border-top-left-radius: 4px;
          border-top-right-radius: 4px;
          border-bottom: 1px solid rgb(225, 225, 225);
          background-repeat: repeat;
        }
        .text {
          height: 60px;
          font-weight: 500;
          text-align: center;
          line-height: 60px;
        }
      }
      .coaching {
        margin-right: 20px;
      }
    }
  }

</style>

