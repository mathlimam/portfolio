<template>
    <div class="h-full w-[98%] m-auto flex items-center justify-center">
        <Card class="w-full h-max py-[3%]">
            <template #content>
                <div class="pb-[3%]">
                    <p class="about-title">ABOUT ME</p>
                    <Divider />
                    <p class="about-detail">Here you will find more information about me, what I do, and my current
                        skills
                        mostly in terms of
                        programming and technology.</p>
                </div>
                <div class="card flex h-[80%] w-[95%] mx-auto">
                    <div class="m-0 w-[48%] justify-center items-center">
                        <p class="card-about-title">Get to know me!</p>
                        <p class="know-content">IBefore transitioning into tech, I had a strong foundation in people management,
                          HR, and financial operations within the construction and industrial maintenance sectors.
                          I was responsible for overseeing the entire HR and payroll departments,
                          ensuring smooth workforce management and compliance.
                          Additionally, my experience in finance equipped me with skills to manage budgets, analyze financial reports, and streamline operational costs.
</p>
                        <p class="know-content">W
                          This background has provided me with a unique blend of strategic thinking,
                          problem-solving, and leadership, which I now bring into the tech field.
                          I leverage this experience to better understand stakeholder needs, manage teams effectively,
                          and deliver solutions that align with business goals.
                          As I pivot to full-stack and back-end development,
                          this holistic view helps me connect the dots between technology and real-world business challenges.</p>
                        <p class="know-content">Check out my <a href="/portfolio/#/projects" target="_blank">Projects</a>
                            section to see
                            some of my work!</p>
                        <p class="know-content">I also enjoy sharing my knowledge about Web Development, Cloud and API with the
                            developer community. You can connect with me on <a
                                href="https://www.linkedin.com/in/math-lima-moreira/" target="_blank">LinkedIn</a> to follow my
                            journey and
                            gain
                            insights from what I’ve learned.</p>
                        <p class="know-content">I’m open to job opportunities where I can contribute, grow, and learn.
                            If you have an
                            exciting opportunity that aligns with my skills and experience, feel free to reach out!</p>
                    </div>

                    <Divider layout="vertical" />

                    <div class="m-0 w-[48%] grid-row mt-[0.5%]">
                        <p class="card-about-title">My Skills</p>
                        <div class="flex flex-wrap mb-auto gap-2">
                            <Tag severity="contrast"><span class="tag">Python</span></Tag>
                            <Tag severity="contrast"><span class="tag">FastAPI</span></Tag>
                            <Tag severity="contrast"><span class="tag">PyDantic</span></Tag>
                            <Tag severity="contrast"><span class="tag">Flask</span></Tag>
                            <Tag severity="contrast"><span class="tag">Pandas</span></Tag>
                            <Tag severity="contrast"><span class="tag">Java</span></Tag>
                            <Tag severity="contrast"><span class="tag">Spring</span></Tag>
                            <Tag severity="contrast"><span class="tag">DevOps</span></Tag>
                            <Tag severity="contrast"><span class="tag">AWS</span></Tag>
                            <Tag severity="contrast"><span class="tag">Docker</span></Tag>
                            <Tag severity="contrast"><span class="tag">CyberSec</span></Tag>
                            <Tag severity="contrast"><span class="tag">HTML</span></Tag>
                            <Tag severity="contrast"><span class="tag">JavaScript</span></Tag>
                            <Tag severity="contrast"><span class="tag">CSS</span></Tag>
                            <Tag severity="contrast"><span class="tag">Vue</span></Tag>
                            <Tag severity="contrast"><span class="tag">TypeScript</span></Tag>
                            <Tag severity="contrast"><span class="tag">Tailwind</span></Tag>
                            <Tag severity="contrast"><span class="tag">Github</span></Tag>
                            <Tag severity="contrast"><span class="tag">JIRA</span></Tag>
                            <Tag severity="contrast"><span class="tag">Agile</span></Tag>
                        </div>
                    </div>
                </div>
            </template>
        </Card>
    </div>
</template>

<script setup lang="ts">
import Card from 'primevue/card';
import Divider from 'primevue/divider';
import Tag from 'primevue/tag';
</script>

<style scoped>
a {
    color: #38d49c;
    font-weight: 600;
}

a:hover {
    color: #3f8b6f;
}

p {
    margin-bottom: 10px;
}

.p-tag {
        --p-tag-padding: 4px 10px 4px 10px;
}
</style>
