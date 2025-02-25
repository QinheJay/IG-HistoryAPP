<script setup>
import { ref } from 'vue';

const block2 = ref(null);

const scrollToBottom = async (frame) => {
    window.scrollTo({ top: frame.clientHeight, behavior: "smooth" });
};
</script>

<template>
    <div class="content">
        <n-flex class="block1" :align="'center'">
            <n-grid class="block1__inner">
                <n-gi :span="8">
                    <n-avatar class="avatar" :size="384" src="https://hillib-cn-1-1259626091.cos.ap-shanghai.myqcloud.com/img/student/qinhe/IG-HistoryAPP/about/Avatar.jpg" />
                </n-gi>
                <n-gi :span="14" :offset="2">
                    <div style="font-size: 128px"><b>Hello!</b></div>
                    <n-p :depth="3" style="font-size: 18px">Hi! My name is Qinhe, and I am a high school student at
                        Shenzhen College of International Education. </n-p>
                    <n-p :depth="3" style="font-size: 18px">I
                        studied the IGCSE History course in 9th and 10th
                        grade, achieving an A* in the official Cambridge exams and ranking first in my grade (1st out of
                        150 students) for two consecutive years.</n-p>
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

            .avatar {
                border-radius: 12px;
                box-shadow: var(--boxShadow-deep);
            }
        }
    }

    .block2 {
        min-height: 100vh;

        .block2__inner {
            align-items: center;
        }
    }
}
</style>