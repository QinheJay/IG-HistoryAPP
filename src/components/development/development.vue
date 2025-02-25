<script setup>
import { ref } from 'vue';

const block2 = ref(null);

const scrollToBottom = async (frame) => {
    window.scrollTo({ top: frame.clientHeight, behavior: "smooth" });
};
</script>

<template>
    <div class="content">
        <n-flex :align="'center'">
            <div class="slogan"><b>Development<br /> History</b></div>
            <n-divider />
            <n-grid :x-gap="24">
                <n-gi :span="6">
                    <h2>January 11, 2025</h2>
                </n-gi>
                <n-gi :span="18">
                    <p></p>
                </n-gi>
            </n-grid>
            <n-divider />
            <n-grid :x-gap="24">
                <n-gi :span="6">
                    <h2>January 11, 2025</h2>
                </n-gi>
                <n-gi :span="18">
                    <p></p>
                </n-gi>
            </n-grid>
            <n-divider />
            <n-grid :x-gap="24">
                <n-gi :span="6">
                    <h2>January 27, 2025</h2>
                </n-gi>
                <n-gi :span="18">
                    <h2>Homepage Layout Completed and Content Adjustments for IG History</h2>
                    <p>Today, I completed the homepage layout for IG History. Since I'm not yet of legal age to join the
                        Apple Developer Program, I decided to have the app project hosted under Scholar Hills' Apple
                        Developer Program. I’ve also set up the necessary details on App Store Connect for the app's
                        upcoming release, including pricing, user agreements, and selection of distribution regions.
                        With these completed, Milestone 1 is now fully finished. Additionally, I’ve designed the first
                        draft of the app icon. </p>
                    <p><n-image style="border-radius: 12px;" src="/IG-HistoryAPP/development/appIconV1.jpg" width="72"></n-image></p>
                    <p><b>Content Adjustments:</b></p>
                    <ol>
                        <li>Removed the flashcard feature.</li>
                        <li>Combined the flashcard section and study materials section under one unified syllabus.</li>
                        <li>Each topic now includes both "Learn" and "Practice" sections.</li>
                        <li>The "Practice" section will include a mistake collection feature (still to be finalized).
                        </li>
                    </ol>
                    <p><b>Next Steps:</b></p>
                    <ol>
                        <li>Organize the relevant PDFs for all topics.</li>
                        <li>Finalize the mistake collection feature for the Practice section.</li>
                        <li>Continue designing and refining the app icon.</li>
                    </ol>
                </n-gi>
            </n-grid>
            <n-divider />
            <n-grid :x-gap="24">
                <n-gi :span="6">
                    <h2>January 11, 2025</h2>
                </n-gi>
                <n-gi :span="18">
                    <h2>Confirming App Features and Setting Milestones for IG History</h2>
                    <p>Today, I finally confirmed the features and content for the IG History app. This app is designed
                        to help students preparing for the Cambridge IGCSE History (0470) exam. It covers two main
                        topics: "Twentieth Century: International Relations since 1919" and "Russia, 1905–41." I decided
                        to make the app a simple and effective revision tool, combining study materials and practice
                        exercises to help students improve their history knowledge in a targeted way.</p>
                    <p>Specifically, the app will have the following features:</p>
                    <ol>
                        <li><b>Study Materials</b>: These will be provided in PDF format to help students consolidate
                            key concepts and background knowledge.</li>
                        <li><b>Past Exam Flashcards</b>: This section will include practice questions from past exams
                            and help students track their progress. Each flashcard will record whether the student
                            answered correctly or incorrectly and generate a list of mistakes for later review.</li>
                    </ol>
                    <p>In addition, I’ve set three milestones for the development process to ensure clear goals at each
                        stage:</p>
                    <ul>
                        <li>
                            <b>Milestone 1</b>:
                            <ul>
                                <li>Joined the Apple Developer Program</li>
                                <li>Created a GitHub repository and initialized the Xcode project</li>
                                <li>Finalized app features</li>
                                <li>Completed the homepage layout</li>
                                <li>Set up page navigation</li>
                            </ul>
                        </li>
                        <li>
                            <b>Milestone 2</b>:
                            <ul>
                                <li>Complete subpages</li>
                                <li>Designed app icon</li>
                                <li>Set up App Store Connect</li>
                            </ul>
                        </li>
                        <li>
                            <b>Milestone 3</b>:
                            <ul>
                                <li>Test the app on TestFlight</li>
                                <li>App distribution</li>
                                <li>App review</li>
                                <li>App release</li>
                            </ul>
                        </li>
                    </ul>
                    <p>I’ve already completed some tasks in Milestone 1, and I’m feeling accomplished. The upcoming
                        tasks will be more challenging, but I’ll keep pushing forward to improve the app. I hope it will
                        help students better prepare for the exam, enhance their history knowledge, and pass with
                        confidence.</p>
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

    .slogan {
        font-size: 96px;
        line-height: 86px;
        letter-spacing: -0.075em;
        word-spacing: 0.1em;
        margin-bottom: 42px;
    }
}
</style>