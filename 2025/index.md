---
layout: page
title: "PkCEP 2025 - Lahore, Pakistan"
permalink: /2025/
---

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        line-height: 1.6;
        color: #333;
        background: #f8f9fa;
        min-height: 100vh;
    }

    .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
    }

    .header {
        background: transparent;
        backdrop-filter: none;
        border-radius: 0;
        padding: 20px 0;
        text-align: center;
        margin-bottom: 30px;
        box-shadow: none;
    }

    .header h1 {
        font-size: 2.5em;
        color: #1a6b3a;
        margin-bottom: 10px;
        font-weight: 700;
    }

    .header .date-location {
        font-size: 1.3em;
        color: #2c8c5a;
        margin-bottom: 15px;
    }

    .header .subtitle {
        font-size: 1.1em;
        color: #34495e;
        font-style: italic;
        margin-bottom: 20px;
    }

    .header .description {
        font-size: 1em;
        color: #555;
        font-weight: 500;
    }

    .agenda-section {
        background: rgba(255, 255, 255, 0.95);
        backdrop-filter: blur(10px);
        border-radius: 15px;
        margin-bottom: 20px;
        overflow: hidden;
        box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .agenda-section:hover {
        transform: translateY(-5px);
        box-shadow: 0 25px 50px rgba(0, 0, 0, 0.15);
    }

    .session-header {
        background: linear-gradient(135deg, #1a6b3a, #2c8c5a);
        color: white;
        padding: 20px;
        display: flex;
        align-items: center;
        gap: 20px;
    }

    .session-time {
        background: rgba(255, 255, 255, 0.2);
        padding: 10px 20px;
        border-radius: 25px;
        font-weight: bold;
        font-size: 1.1em;
        min-width: 120px;
        text-align: center;
    }

    .session-speaker {
        font-size: 1.3em;
        font-weight: 600;
    }

    .session-title {
        font-size: 1.1em;
        opacity: 0.9;
        margin-top: 5px;
    }

    .session-content {
        padding: 30px;
    }

    .abstract {
        margin-bottom: 30px;
    }

    .abstract h3 {
        color: #2c3e50;
        margin-bottom: 15px;
        font-size: 1.2em;
        border-bottom: 2px solid #4ad98a;
        padding-bottom: 5px;
        display: inline-block;
    }

    .abstract p {
        color: #555;
        text-align: justify;
        margin-bottom: 15px;
    }

    .speaker-bio {
        background: #f0f7f0;
        border-radius: 10px;
        padding: 20px;
        border-left: 4px solid #4ad98a;
    }

    .speaker-bio h3 {
        color: #2c3e50;
        margin-bottom: 15px;
        font-size: 1.2em;
    }

    .speaker-bio p {
        color: #666;
        text-align: justify;
    }

    .panel-session {
        background: linear-gradient(135deg, #e67e22, #d35400);
    }

    .panel-session .session-time {
        background: rgba(255, 255, 255, 0.3);
    }

    .coming-soon {
        background: #fff3cd;
        border: 1px solid #ffeaa7;
        border-radius: 8px;
        padding: 15px;
        margin: 15px 0;
        color: #856404;
        font-style: italic;
        text-align: center;
    }

    @media (max-width: 768px) {
        .container {
            padding: 10px;
        }

        .header {
            padding: 20px;
        }

        .header h1 {
            font-size: 2em;
        }

        .session-header {
            flex-direction: column;
            text-align: center;
            gap: 10px;
        }

        .session-time {
            min-width: auto;
        }

        .session-content {
            padding: 20px;
        }
    }

    .toc {
        background: rgba(255, 255, 255, 0.95);
        backdrop-filter: blur(10px);
        border-radius: 15px;
        padding: 30px;
        margin-bottom: 30px;
        box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
    }

    .toc h2 {
        color: #1a6b3a;
        margin-bottom: 20px;
        text-align: center;
        font-size: 1.5em;
    }

    .toc ul {
        list-style: none;
        padding: 0;
    }

    .toc li {
        margin-bottom: 10px;
        padding: 10px;
        background: #f0f7f0;
        border-radius: 8px;
        border-left: 4px solid #4ad98a;
    }

    .toc .time {
        font-weight: bold;
        color: #2c8c5a;
        display: inline-block;
        width: 100px;
    }

    .toc .speaker {
        font-weight: 600;
        color: #2c3e50;
    }

    .toc .title {
        color: #666;
        font-style: italic;
    }

    .panelists-section {
        margin: 30px 0;
    }

    .panelists-section h3 {
        color: #2c3e50;
        margin-bottom: 20px;
        font-size: 1.2em;
        border-bottom: 2px solid #4ad98a;
        padding-bottom: 5px;
        display: inline-block;
    }

    .panelist-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 20px;
        margin-top: 20px;
    }

    .panelist-card {
        background: #f0f7f0;
        border-radius: 10px;
        padding: 20px;
        border-left: 4px solid #4ad98a;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .panelist-card:hover {
        transform: translateY(-3px);
        box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
    }

    .panelist-card h4 {
        color: #2c3e50;
        margin-bottom: 8px;
        font-size: 1.1em;
        font-weight: 600;
    }

    .affiliation {
        color: #2c8c5a;
        font-weight: 500;
        margin-bottom: 12px;
        font-style: italic;
    }

    .panelist-card p {
        color: #666;
        line-height: 1.5;
        margin: 0;
    }

    @media (max-width: 768px) {
        .panelist-grid {
            grid-template-columns: 1fr;
            gap: 15px;
        }
        
        .panelist-card {
            padding: 15px;
        }
    }
</style>

<div class="container">
    <header class="header">
        <h1>Computing Education Practice in Pakistan</h1>
        <div class="date-location">26th July 2025, LUMS, Lahore, Pakistan</div>
        <div class="subtitle">A one-day hybrid workshop on the practice of computing education in Pakistan</div>
        <div class="description">Full Agenda, Summary of Talks, and Speaker Biographies</div>
    </header>

    <section class="toc">
        <h2>Conference Schedule</h2>
        <ul>
            <li><span class="time">9:30-10:00</span> <span class="speaker">Ethel Tshukudu</span> - <span class="title">Broadening Participation in Computing Education</span></li>
            <li><span class="time">10:00-10:30</span> <span class="speaker">Sarfraz Raza</span> - <span class="title">Introducing Programming to Beginners</span></li>
            <li><span class="time">10:30-11:00</span> <span class="speaker">Muhammad Hamad Alizai</span> - <span class="title">Teaching Computer Science at Scale</span></li>
            <li><span class="time">11:30-12:00</span> <span class="speaker">Mobin Javed and Maryam Ghafoor</span> - <span class="title">How We Designed a CS Course for Industry Success</span></li>
            <li><span class="time">12:00-12:30</span> <span class="speaker">Matthew Barr</span> - <span class="title">Delivering a Work-Based Learning Degree Programme</span></li>
            <li><span class="time">12:30-13:15</span> <span class="speaker">Panel discussion</span> - <span class="title">Computing Education in Pakistan – Going Forward in the age of AI</span></li>
        </ul>
    </section>


    <article class="agenda-section">
        <div class="session-header">
            <div class="session-time">9:30-10:00</div>
            <div>
                <div class="session-speaker">Ethel Tshukudu</div>
                <div class="session-title">Broadening Participation in Computing Education: Lessons from the CSEdBotswana Initiative</div>
            </div>
        </div>
        <div class="session-content">
            <div class="abstract">
                <h3>Abstract</h3>
                <p>In many parts of the world, access to quality computing education remains uneven, especially at the K–12 and tertiary levels. Since 2022, the CSEdBotswana initiative has worked to close these gaps through national-scale interventions focused on broadening participation in computing across schools in Botswana. As founder of the initiative, I will share how we have grown from a small grassroots effort into a movement that has reached hundreds of schools, trained hundreds of teachers, and engaged thousands of students in coding activities across multiple years.</p>
                <p>The talk will highlight key strategies that have enabled this work, including the use of contextualized programming learning materials, bilingual programming approaches, and unplugged activities that allow schools with limited infrastructure to participate fully. We have implemented scalable activities like Hour of Code, teacher workshops, teacher trainings, summit, all tailored to school level and local realities. Our experience shows that even with challenges and limited funding, community-driven models can lead to strong teacher and student engagement, capacity building, and sustained interest in computing.</p>
            </div>
            <div class="speaker-bio">
                <h3>About the Speaker</h3>
                <p>Dr. Ethel Tshukudu is an Assistant Professor of Computer Science and Science Education at San José State University and a member of the ACM SIGCSE Board. She earned her PhD from the University of Glasgow, where she studied conceptual transfer in learning new programming languages. Ethel is the founder of CSEdBotswana, a national initiative focused on broadening participation in computing through non-formal teacher training and student outreach. She has also worked with the Raspberry Pi Foundation and served as a research visitor at the University of Cambridge, contributing to global computing education efforts. Her research explores conceptual transfer, AI/ML in education, and the contextualization of computing education as well as bilingual programming for bilingual learners.</p>
            </div>
        </div>
    </article>

    <article class="agenda-section">
        <div class="session-header">
            <div class="session-time">10:00-10:30</div>
            <div>
                <div class="session-speaker">Sarfraz Raza</div>
                <div class="session-title">Introducing Programming to Beginners</div>
            </div>
        </div>
        <div class="session-content">
            <div class="abstract">
                <h3>Abstract</h3>
                <p>This talk dives into why programming is so hard for novices and why much of the blame lies not with them, but with how we teach it. Syntax errors, logic bugs, confusing explanations, and a growing sense of "I'm just not a coding person" are all part of the typical novice experience. But beyond those superficial challenges lies something deeper: a disconnect between student needs and instructional design. From young children to undergraduates, students face different learning challenges, yet we often teach them all the same way.</p>

                <p>Why is there a disconnect between what students need and how we teach? Why do so many educators focus on limited correction of errors in programs and pseudo-code, while missing the opportunities these mistakes represent to improve their foundational conceptual understanding by building connections with pre-existing knowledge? And why do we assume students are ready to "think computationally" when we've never explicitly taught them what that means?</p>

                <p>We'll take a fresh look at common struggles, re-design some teaching methods with declining pedagogical value, and explore some age-appropriate strategies to better support learners. Specifically, the key challenges faced by K2-K5 (primary school), K6-K12 (middle school to high school), and undergraduate learners will be discussed along with how the challenges of each level should be addressed through more tailored pedagogical approaches.</p>
                <p>If we want our students to succeed in programming, we can't just fix their bugs, we have to fundamentally debug the way we teach.</p>
            </div>
            <div class="speaker-bio">
                <h3>About the Speaker</h3>
                <p>Teaching Fellow ITU Lahore, CEO Seedprogramming.org (More details to follow).</p>
            </div>
        </div>
    </article>

    <article class="agenda-section">
        <div class="session-header">
            <div class="session-time">10:30-11:00</div>
            <div>
                <div class="session-speaker">Muhammad Hamad Alizai</div>
                <div class="session-title">Teaching Computer Science at Scale</div>
            </div>
        </div>
        <div class="session-content">
            <div class="abstract">
                <h3>Abstract</h3>
                <p>The dramatic global surge in computer science enrollments has outpaced universities' ability to expand faculty lines, a gap that is particularly acute in Pakistan, where attracting and retaining top-tier academic talent remains challenging. This presentation reports on LUMS' strategic adoption of a large-class teaching model designed to sustain program quality while accommodating rapid growth. Central to the model's success was an integrated suite of pedagogical trainings, covering evidence-based active-learning techniques, formative assessment at scale, and technology-enabled feedback loops, that equipped faculty and teaching assistants to manage cohorts exceeding 300 students without compromising learning outcomes.</p>
                <p>The LUMS experience offers transferable insights for similar resource-constrained contexts, demonstrating how deliberate pedagogical capacity-building can mitigate faculty shortages and enable high-quality computer science education at scale.</p>
            </div>
            <div class="speaker-bio">
                <h3>About the Speaker</h3>
                <p>Muhammad Hamad Alizai is Associate Professor and Chair of Computer Science at SBASSE, LUMS. He is also the Director of LUMS Learning Institute (LLI).</p>
            </div>
        </div>
    </article>

    <article class="agenda-section">
        <div class="session-header">
            <div class="session-time">11:30-12:00</div>
            <div>
                <div class="session-speaker">Mobin Javed and Maryam Ghafoor</div>
                <div class="session-title">How We Designed a CS Course for Industry Success</div>
            </div>
        </div>
        <div class="session-content">
            <div class="abstract">
                <h3>Abstract</h3>
                <p>Last fall, we launched a new course at LUMS aimed at preparing students for competitive technical interviews. The course provided students with over 80 hours of coding practice and honed their problem-solving and interviewing skills. It also offered exposure to both local and international hiring landscapes through industry panels and guest lectures.</p>
                <p>To provide authentic interview practice, we designed homework assignments around peer mock interviews, trained a team of teaching fellows to conduct mid-semester interviews, and partnered with LUMS CS alumni working in the industry to conduct final mock interviews.</p>
                <p>Taken by nearly 100 senior students, the course received highly positive feedback. In this talk, we will share how we designed and executed the course, including: the problem-solving session template we developed, the grading rubrics we used, and how we managed the complex logistics of conducting multiple rounds of mock interviews.</p>
            </div>
            <div class="speaker-bio">
                <h3>About the Speaker</h3>
                <p>Mobin Javed is an Associate Professor in the Computer Science department at the Lahore University of Management Sciences (LUMS), Pakistan. Her research focuses on security, privacy, and Internet measurement, and has won several awards including the IAPP SOUPS Privacy Award 2023, the Applied Networking Research Prize 2020, and the Internet Defense Prize 2017. She serves on the Program Committee of several top-tier security and networking conferences including IMC, SIGCOMM, Usenix Security, CCS, and PETS. She was also the TPC co-chair for IMC 2023.</p>
            </div>
        </div>
    </article>

    <article class="agenda-section">
        <div class="session-header">
            <div class="session-time">12:00-12:30</div>
            <div>
                <div class="session-speaker">Matthew Barr</div>
                <div class="session-title">Delivering a Work-Based Learning Degree Programme in Software Engineering: Lessons from Practice</div>
            </div>
        </div>
        <div class="session-content">
            <div class="abstract">
                <h3>Abstract</h3>
                <p>Traditional university computing programmes often struggle to prepare graduates for the realities of industry, while simultaneously failing to provide accessible pathways for students from disadvantaged backgrounds. This talk presents our experience of delivering a work-based learning degree programme in Software Engineering at the University of Glasgow, where students spend 80% of their time as apprentices in industry while completing an honours degree over four years.</p>
                <p>Drawing on studies conducted over the programme's seven-year history, the talk will demonstrate how degree apprenticeships serve a dual purpose: widening access to higher education and developing industry-ready professionals. Our analysis of students from Scotland's most deprived areas reveals that apprenticeships provide crucial "second chances" for those poorly served by traditional education pathways, while removing financial barriers that typically limit participation in computing degrees.</p>
                <p>Central to our approach is the development of professional skills through reflective practice. Our analysis of student reflections across four years reveals how workplace experience and university education create a powerful bidirectional learning dynamic. Students develop confidence and foundational skills at university that enable them to thrive in the workplace, while real-world experience provides context that enriches their academic understanding. Through structured reflection, students transform tacit workplace learning into explicit, transferable knowledge.</p>
                <p>We share practical insights into programme design, including our consultation with industry, the integration of professional competency frameworks, and assessment approaches that recognise workplace learning. We also address persistent challenges, such as the gap between academic and industry project expectations, and the difficulty some students face in transferring advanced technical skills between contexts.</p>
                <p>This talk offers guidance for educators, policymakers, and industry partners interested in implementing or supporting work-based learning programmes. It demonstrates that when thoughtfully designed, such programmes can simultaneously address skills gaps, improve educational access, and create transformative opportunities for students who might otherwise be excluded from computing careers.</p>
            </div>
            <div class="speaker-bio">
                <h3>About the Speaker</h3>
                <p>Dr Matthew Barr is a Senior Lecturer at the University of Glasgow. He is head of the Education and Practice (EAP) section in the School of Computing Science, where he leads the Graduate Apprenticeship in Software Engineering programme and chairs the School's Industry Advisory Board. Matt is also co-director of the University's Games and Gaming Lab, a Senior Fellow in Recognising Excellence in Teaching (RET), and a member of the University's Teaching Excellence Network. He previously convened the University's first game studies course and founded the international student game studies journal, Press Start. He was appointed Director of Education for SICSA (the Scottish Informatics & Computer Science Alliance) in 2021, and is a founding editor of the journal, Open Scholarship of Teaching and Learning.</p>
                <p>Matt is the founder of the Ada Scotland Festival, which aims to improve gender balance in Computing Science education across Scotland. He also champions inclusion and diversity through his membership of several Scotland-wide groups, including the Scottish Apprenticeship Advisory Board Equalities Group, and the Scottish Government's Digital Economy Skills Group and National Digital Ethics Expert Group. He is also involved in related work through Skills Development Scotland, including the Tackling the Technology Gender Gap Together (TTGGT) workstream, the Neurodiversity Steering Group, and the Women into Tech Steering Group. Matt previously served as Vice Chair of British DiGRA (the Digital Games Research Association) and as a Trustee and Director of the Scottish Game Developers Association. Until 2022, Matt was a member of the BAFTA Scotland Committee, where he acted as the Games Jury Chair.</p>
                <p>Matt's games research, which has attracted significant media attention, examines how video games may be used to develop skills and competencies such as critical thinking, adaptability, and communication skills. This work received the Association for Learning Technology's inaugural Research Project of the Year award in 2018 and forms the basis of his first book, Graduate Skills and Game-Based Learning, published with Palgrave in 2019. An edited volume, Approaches to Work-Based Learning in Higher Education: Improving Graduate Employability, was published with Taylor & Francis in 2024.</p>
            </div>
        </div>
    </article>

    <article class="agenda-section">
        <div class="session-header panel-session">
            <div class="session-time">12:30-13:15</div>
            <div>
                <div class="session-speaker">Computing Education in Pakistan – Going Forward in the age of AI</div>
                <div class="session-title">Panel Discussion</div>
            </div>
        </div>
        <div class="session-content">
            <div class="abstract">
                <h3>Panel Discussion</h3>
                <p>This panel discussion will explore the future of computing education in Pakistan, with a particular focus on how artificial intelligence is reshaping the landscape of computer science education and its implications for educational practices, curriculum development, and student preparation.</p>
            </div>
            
            <div class="panelists-section">
                <h3>Panelists</h3>
                <div class="panelist-grid">
                    <div class="panelist-card">
                        <h4>Yasser Basir</h4>
                        <div class="affiliation">Arbisoft</div>
                        <p>Yasser Bashir is the CEO of Arbisoft.</p>
                    </div>
                    
                    <div class="panelist-card">
                        <h4>Dr. Fakhar-ul-Islam Lodhi</h4>
                        <div class="affiliation">The Children's Place</div>
                        <p>Dr. Fakhar is a seasoned professional and professor. Presently, he is Director of Delivery at The Children's Place.</p>
                    </div>
                    
                    <div class="panelist-card">
                        <h4>Dr. Zeeshan Ali Rana</h4>
                        <div class="affiliation">NUCES, Lahore</div>
                        <p>Dr. Zeeshan is an experienced professor, and Incharge of Software Engineering and National University of Computer and Emerging Science, Lahore Campus.</p>
                    </div>
                </div>
            </div>
            <div class="panelists-section">
                <h3>Panel Moderator</h3>
                <div class="panelist-grid">
                    <div class="panelist-card">
                        <h4>Rabia Sirhindi</h4>
                        <div class="affiliation">Educative</div>
                        <p>Rabia Sirhindi is an experience university educator and is presently a Content Architect Lead at Educative.</p>
                    </div>
                    
                </div>
            </div>
        </div>
    </article>
</div>