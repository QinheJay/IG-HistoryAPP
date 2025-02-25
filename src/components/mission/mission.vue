<script setup>
</script>

<template>
    <div class="content">
        <n-flex class="block1" :align="'center'">
            <div class="block1__inner">
                <h2 style="color: var(--primary-color)">Why did I make this?</h2>
                <p>When I was preparing for my Cambridge IGCSE History (0470) exams, I faced the same struggles that
                    many students do—textbooks were either too detailed and overwhelming or too simplified, lacking
                    the depth needed to write strong, evidence-based essays. I spent countless hours
                    cross-referencing multiple sources, piecing together notes, and searching for practice questions
                    that actually reflected the exam format. That’s when I realized: there had to be a better way.
                </p>
                <p>That’s why I created IG History—the app I wish I had when I was studying. It provides concise yet
                    comprehensive revision notes and exam-style practice questions, specifically tailored to the
                    official Cambridge IGCSE syllabus. Covering both the “Twentieth Century: International Relations
                    since 1919” Core Content and the “Russia, 1905–41” Depth Study, this app helps you focus on what
                    actually matters for the exam.</p>
                <h2 style="color: var(--primary-color)">Mission</h2>
                <p>To make studying more effective, I designed IG History with two essential sections:</p>
                <n-grid :x-gap="12">
                    <n-gi :span="2">
                        <n-icon :size="24">
                            <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                                viewBox="0 0 24 24">
                                <path d="M9 16.17L4.83 12l-1.42 1.41L9 19L21 7l-1.41-1.41L9 16.17z" fill="currentColor">
                                </path>
                            </svg>
                        </n-icon>
                    </n-gi>
                    <n-gi :span="22">Learn – This section contains clear, well-structured notes that I personally
                        wrote,
                        covering key historical evidence that students can use in their studies and essays. The
                        content is designed to be precise yet detailed enough to help you construct strong arguments
                        in the exam.</n-gi>
                </n-grid>
                <n-grid :x-gap="12">
                    <n-gi :span="2">
                        <n-icon :size="24">
                            <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                                viewBox="0 0 24 24">
                                <path d="M9 16.17L4.83 12l-1.42 1.41L9 19L21 7l-1.41-1.41L9 16.17z" fill="currentColor">
                                </path>
                            </svg>
                        </n-icon>
                    </n-gi>
                    <n-gi :span="22">Practice – Here, I compiled challenging and commonly tested past paper
                        questions from the
                        0470 exam. You can check the answers by simply flipping the question card, and with the
                        bookmark feature, you can save questions you find difficult into a personal folder for later
                        review. This allows you to track your progress and revisit tricky topics whenever
                        needed.</n-gi>
                </n-grid>
                <p>Since this is my first time coding an app, I truly appreciate any feedback you might have—whether
                    about the content or how the app functions. If you have any suggestions or encounter any issues,
                    feel free to reach out to me at Qinheyang10086@outlook.com.</p>
                <p>I hope IG History makes your revision easier and more effective. Good luck on your exams!</p>
                <p style="text-align: right;">— <b>Qinhe</b></p>
            </div>
        </n-flex>
    </div>
</template>

<style lang="less" scoped>
.content {
    width: 720px;
    margin: 0 auto;
    padding: 24px;
}
</style>