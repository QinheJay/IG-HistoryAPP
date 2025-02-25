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
                    <p><n-image style="border-radius: 12px;" src="./IG-HistoryAPP/development/appIconV1.jpg"
                            width="72"></n-image></p>
                    <p><b>Content Adjustments:</b></p>
                    <ol>
                        <li>
                            <p>Removed the flashcard feature.</p>
                        </li>
                        <li>
                            <p>Combined the flashcard section and study materials section under one unified
                                syllabus.</p>
                        </li>
                        <li>
                            <p>Each topic now includes both "Learn" and "Practice" sections.</p>
                        </li>
                        <li>
                            <p>The "Practice" section will include a mistake collection feature (still to be
                                finalized).</p>
                        </li>
                    </ol>
                    <p><b>Next Steps:</b></p>
                    <ol>
                        <li>
                            <p>Organize the relevant PDFs for all topics.</p>
                        </li>
                        <li>
                            <p>Finalize the mistake collection feature for the Practice section.</p>
                        </li>
                        <li>
                            <p>Continue designing and refining the app icon.</p>
                        </li>
                    </ol>
                </n-gi>
            </n-grid>
            <n-divider />
            <n-grid :x-gap="24">
                <n-gi :span="6">
                    <h2>January 15, 2025</h2>
                </n-gi>
                <n-gi :span="18">
                    <h2>Understanding iOS App Development Process and Completing Milestone 1 Tasks</h2>
                    <p>Today, I took the time to understand all the necessary steps and tools required to develop and
                        launch an iOS app. I completed the following tasks for Milestone 1:</p>
                    <ol>
                        <li>
                            <p>Created a GitHub repository and initialized the Xcode project.</p>
                        </li>
                        <li>
                            <p>Finalized the app features.</p>
                        </li>
                        <li>
                            <p>Completed the navigation between pages.</p>
                        </li>
                        <li>
                            <p>Developed initial prototypes for the "Study Materials" page and the "Flashcards" page.
                            </p>
                        </li>
                    </ol>
                    <p>Moving forward, I will continue to refine the display details for each page based on the initial
                        prototypes and work on rendering the PDFs for the "Study Materials" section. I will also focus
                        on enhancing the user interactions for the "Flashcards" section.</p>
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
                        <li>
                            <p><b>Study Materials</b>: These will be provided in PDF format to help students consolidate
                                key concepts and background knowledge.</p>
                        </li>
                        <li>
                            <p><b>Past Exam Flashcards</b>: This section will include practice questions from past exams
                                and help students track their progress. Each flashcard will record whether the student
                                answered correctly or incorrectly and generate a list of mistakes for later review.</p>
                        </li>
                    </ol>
                    <p>In addition, I’ve set three milestones for the development process to ensure clear goals at each
                        stage:</p>
                    <ul>
                        <li>
                            <b>Milestone 1</b>:
                            <ul>
                                <li>
                                    <p>Joined the Apple Developer Program</p>
                                </li>
                                <li>
                                    <p>Created a GitHub repository and initialized the Xcode project</p>
                                </li>
                                <li>
                                    <p>Finalized app features</p>
                                </li>
                                <li>
                                    <p>Completed the homepage layout</p>
                                </li>
                                <li>
                                    <p>Set up page navigation</p>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <b>Milestone 2</b>:
                            <ul>
                                <li>
                                    <p>Complete subpages</p>
                                </li>
                                <li>
                                    <p>Designed app icon</p>
                                </li>
                                <li>
                                    <p>Set up App Store Connect</p>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <b>Milestone 3</b>:
                            <ul>
                                <li>
                                    <p>Test the app on TestFlight</p>
                                </li>
                                <li>
                                    <p>App distribution</p>
                                </li>
                                <li>
                                    <p>App review</p>
                                </li>
                                <li>
                                    <p>App release</p>
                                </li>
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