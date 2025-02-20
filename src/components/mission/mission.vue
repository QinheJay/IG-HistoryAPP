<script setup>
</script>

<template>
    <div class="content">
        <n-flex class="block1" :align="'center'">
            <n-grid class="block1__inner">
                <n-gi :span="12">
                    <div class="slogan"><b>I APTENT LEO<br /> MAXIMUS <span style="color: red">RED</span>
                            DUIS</b></div>
                </n-gi>
                <n-gi :span="10" :offset="2">
                    <h2>Why did I make this?</h2>
                    <p>Id imperdiet ac nascetur hendrerit eros congue donec urna. Cursus aliquam per suscipit
                        adipiscing, sapien laoreet parturient. Posuere suscipit class senectus maximus sodales accumsan
                        cubilia a vel.
                    </p>
                    <p>Magnis inceptos ad posuere porta scelerisque. Metus mauris ullamcorper in sapien litora massa
                        interdum accumsan. Risus quis ad tempus parturient ornare dictum. Orci ex nam facilisi, nisl
                        fusce semper ultrices consectetur. </p>
                    <p>
                        Efficitur magnis lectus mus; <b>vulputate cursus turpis lacus praesent</b>. Dictum sociosqu mus
                        nec
                        arcu diam duis fusce.</p>
                    <h2>Mission</h2>
                    <p>My mission is simple: Conubia mus orci ex sapien erat. Pellentesque tellus condimentum aliquet
                        convallis nulla felis netus.</p>
                </n-gi>
            </n-grid>
        </n-flex>
    </div>
</template>

<style lang="less" scoped>
.content {
    width: 1200px;
    margin: 0 auto;
    padding: 24px;

    .block1 {
        min-height: calc(100vh - 87px - 48px);

        .block1__inner {
            margin-top: -87px;
            align-items: center;

            .slogan {
                font-size: 96px;
                line-height: 86px;
                letter-spacing: -0.075em;
                word-spacing: 0em;
            }
        }
    }

    .block2 {
        height: 100vh;

        .block2__inner {
            align-items: center;
        }
    }

    .block3 {
        height: 100vh;

        .block3__inner {
            align-items: center;
        }
    }

    .block4 {
        height: 100vh;

        .block4__inner {
            align-items: center;
        }
    }

    .showdetail {
        .n-image {
            border: 2px solid black;
            box-shadow: var(--boxShadow-deep);
            border-radius: 20px;
        }
    }
}
</style>