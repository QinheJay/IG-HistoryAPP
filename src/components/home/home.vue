<script setup>
</script>

<template>
    <div class="content">
        <n-flex class="block1" :align="'center'">
            <div style="margin-top: -87px">
                <n-grid style="align-items: center;">
                    <n-gi :span="12">
                        <n-flex :justify="'center'">
                            <n-image :width="220" src="https://hillib-cn-1-1259626091.cos.ap-shanghai.myqcloud.com/img/student/qinhe/IG-HistoryAPP/home/appHome.png"
                                preview-disabled></n-image>
                        </n-flex>
                    </n-gi>
                    <n-gi :span="12">
                        <div>
                            <div class="slogan">Welcome to IG History</div>
                            <div class="subtitle">Your Ultimate IGCSE History Companion</div>
                            <p>IG History is an app specifically designed to support students preparing for the
                                Cambridge IGCSE History (0470) exam. It currently includes comprehensive revision notes
                                and exam-style practice questions for every unit in the “Twentieth Century:
                                International Relations since 1919” Core Content and the “Russia, 1905–41” Depth Study.
                            </p>
                        </div>
                        <div>
                            <n-button type="primary" round class="startBtn" href="https://apps.apple.com/us/app/ig-history/id6741053306" tag="a" target="_blank">
                                Start Here
                            </n-button>
                        </div>
                    </n-gi>
                </n-grid>
            </div>
        </n-flex>
    </div>
</template>

<style lang="less" scoped>
.content {
    width: 1200px;
    margin: 0 auto;
    padding: 24px;

    .n-image {
        border-radius: 3px;
    }

    .block1 {
        min-height: calc(100vh - 87px - 48px);

        .slogan {
            font-size: 36px;
            font-weight: bold;
            line-height: 1.4;
        }

        .subtitle {
            margin-top: 48px;
            margin-bottom: 24px;
            font-size: 18px;
        }

        .startBtn {
            margin-top: 12px;
        }
    }

    .block2 {
        min-height: 100vh;

        .n-grid {
            align-items: center;
        }
    }

    .block3 {
        min-height: 100vh;
    }
}
</style>