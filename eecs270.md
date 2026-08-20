---
layout: default
title: EECS 270 - Robot Algorithms
permalink: /teaching/eecs270/
---

<div class="course-hero">
  <div class="course-hero-eyebrow"><a href="{{ '/teaching' | relative_url }}">&larr; Teaching</a></div>
  <h1>EECS 270: Robot Algorithms</h1>
  <p class="course-hero-sub">UC Merced &middot; Most recent offering: Fall 2025 &middot; Prof. Ross Greer</p>
  <p class="course-hero-tag">A hands-on tour of the algorithms that let robots perceive, plan, and act &mdash; from rigid-body transforms to SLAM, LQR, and MPC.</p>
</div>

<div class="quickfacts">
  <div class="qf-card">
    <div class="qf-label">Instructor</div>
    <div class="qf-value">Prof. Ross Greer</div>
    <div class="qf-sub"><a href="mailto:rossgreer@ucmerced.edu">rossgreer@ucmerced.edu</a></div>
  </div>
  <div class="qf-card">
    <div class="qf-label">Office Hours</div>
    <div class="qf-value">Mon 12:00&ndash;12:30 PM</div>
    <div class="qf-sub">SE2 209 &middot; and by appointment</div>
  </div>
  <div class="qf-card">
    <div class="qf-label">Communication</div>
    <div class="qf-value">Piazza</div>
    <div class="qf-sub">All announcements posted there</div>
  </div>
  <div class="qf-card">
    <div class="qf-label">Lab</div>
    <div class="qf-value">Demo &amp; Race Days</div>
    <div class="qf-sub">Robot tasks + cumulative report</div>
  </div>
</div>

<nav class="syllabus-nav" aria-label="Syllabus sections">
  <a href="#about">About</a>
  <a href="#staff">Staff</a>
  <a href="#schedule">Schedule</a>
  <a href="#grading">Grading</a>
  <a href="#labs">Labs</a>
  <a href="#presentation">Presentation</a>
  <a href="#exams">Exams</a>
  <a href="#policies">Policies</a>
  <a href="#resources">Resources</a>
  <a href="#faq">FAQ</a>
</nav>

<section id="about" class="syllabus-section">
  <h2>About this course</h2>
  <p>How does a robot figure out where it is, what's around it, and what to do next? EECS 270 introduces the algorithms behind autonomous robots &mdash; the mathematics and code that turn sensor readings into decisions and decisions into motion.</p>
  <p>Each week we work across the <strong>perception &rarr; planning &rarr; control</strong> pipeline: rigid-body transforms, reactive methods, mapping and localization, state estimation, Bayesian filtering, SLAM, computer vision and machine learning, and modern control (LQR, MPC). Every topic below could easily fill a semester on its own &mdash; we'll cover breadth with enough depth to build and defend a working robot.</p>

  <h3>Course topics</h3>
  <ul class="clean-list">
    <li>Introduction: robot tasks and algorithms in perception, planning, and control</li>
    <li>Rigid body transforms</li>
    <li>Reactive methods</li>
    <li>Mapping and localization</li>
    <li>State estimation</li>
    <li>Bayesian filtering</li>
    <li>SLAM</li>
    <li>Vision &amp; machine learning</li>
    <li>Linear Quadratic Regulator (LQR)</li>
    <li>Model Predictive Control (MPC)</li>
    <li>Special topics driven by student interest</li>
  </ul>
</section>

<section id="staff" class="syllabus-section">
  <h2>Course staff</h2>
  <div class="staff-grid">
    <div class="staff-card">
      <div class="staff-role">Instructor</div>
      <div class="staff-name">Prof. Ross Greer</div>
      <div class="staff-detail">SE2 209 &middot; OH: Mon 12:00&ndash;12:30 PM (and by appointment)</div>
      <div class="staff-detail"><a href="mailto:rossgreer@ucmerced.edu">rossgreer@ucmerced.edu</a></div>
    </div>
    <div class="staff-card">
      <div class="staff-role">Teaching Assistants</div>
      <div class="staff-name">TBD</div>
      <div class="staff-detail">Announced before the semester begins</div>
    </div>
  </div>
  <p class="staff-note"><strong>How to reach us:</strong> use <strong>Piazza</strong> for course questions so the whole class benefits. Please search before posting &mdash; your question may already be answered. Email is for private matters (grading concerns, accommodations, personal circumstances), and email about course material should include a link to the corresponding Piazza post.</p>
</section>

<section id="schedule" class="syllabus-section">
  <h2>Key dates</h2>
  <p class="muted">Dates below reflect the most recent offering. Specifics for the next offering will be confirmed in the first week.</p>
  <div class="dates-grid">
    <div class="date-item">
      <div class="date-when">Wed, Oct 1</div>
      <div class="date-what"><strong>Midterm 1</strong></div>
    </div>
    <div class="date-item">
      <div class="date-when">Sat, Oct 11</div>
      <div class="date-what"><strong>Demo Day 1</strong></div>
    </div>
    <div class="date-item">
      <div class="date-when">Tue, Oct 28</div>
      <div class="date-what"><strong>Demo Day 2</strong></div>
    </div>
    <div class="date-item">
      <div class="date-when">Sat, Nov 1</div>
      <div class="date-what"><strong>Demo Day 3</strong></div>
    </div>
    <div class="date-item">
      <div class="date-when">Wed, Nov 5</div>
      <div class="date-what"><strong>Midterm 2</strong></div>
    </div>
    <div class="date-item">
      <div class="date-when">Tue, Nov 25</div>
      <div class="date-what"><strong>Demo Day 4</strong></div>
    </div>
    <div class="date-item final">
      <div class="date-when">Tue, Dec 9</div>
      <div class="date-what"><strong>Race Day + Final Exam</strong></div>
    </div>
  </div>
</section>

<section id="grading" class="syllabus-section">
  <h2>How you'll be graded</h2>

  <div class="grade-breakdown">
    <div class="grade-row">
      <div class="grade-label">Lab Demonstrations</div>
      <div class="grade-bar"><div class="grade-fill" style="width:20%"></div></div>
      <div class="grade-pct">20%</div>
    </div>
    <div class="grade-row">
      <div class="grade-label">Lab Report</div>
      <div class="grade-bar"><div class="grade-fill" style="width:20%"></div></div>
      <div class="grade-pct">20%</div>
    </div>
    <div class="grade-row">
      <div class="grade-label">Research Presentation</div>
      <div class="grade-bar"><div class="grade-fill" style="width:10%"></div></div>
      <div class="grade-pct">10%</div>
    </div>
    <div class="grade-row">
      <div class="grade-label">Midterm Exams (2 &times; 15%)</div>
      <div class="grade-bar"><div class="grade-fill" style="width:30%"></div></div>
      <div class="grade-pct">30%</div>
    </div>
    <div class="grade-row">
      <div class="grade-label">Final Exam</div>
      <div class="grade-bar"><div class="grade-fill" style="width:20%"></div></div>
      <div class="grade-pct">20%</div>
    </div>
    <div class="grade-row bonus">
      <div class="grade-label">Participation bonus</div>
      <div class="grade-bar"><div class="grade-fill bonus-fill" style="width:2.5%"></div></div>
      <div class="grade-pct">+ up to 2.5%</div>
    </div>
  </div>

  <p><strong>Midterm grace:</strong> your highest midterm score replaces your lowest &mdash; effectively a free-pass midterm if you need to miss one.</p>

  <h3>Grade scale</h3>
  <div class="grade-scale">
    <span><strong>A</strong> 93&ndash;100</span>
    <span><strong>A&minus;</strong> 90&ndash;92</span>
    <span><strong>B+</strong> 87&ndash;89</span>
    <span><strong>B</strong> 83&ndash;86</span>
    <span><strong>B&minus;</strong> 80&ndash;82</span>
    <span><strong>C+</strong> 77&ndash;79</span>
    <span><strong>C</strong> 73&ndash;76</span>
    <span><strong>C&minus;</strong> 70&ndash;72</span>
    <span><strong>D+</strong> 67&ndash;69</span>
    <span><strong>D</strong> 63&ndash;66</span>
    <span><strong>D&minus;</strong> 60&ndash;62</span>
    <span><strong>F</strong> &lt; 60</span>
  </div>
  <p class="muted">An A+ category, reserved for exceptional performance, is determined at the end of the semester.</p>
</section>

<section id="labs" class="syllabus-section">
  <h2>Labs</h2>

  <p>Every student is expected to <strong>understand and be able to explain</strong> what their robot is doing. The lab has two components:</p>

  <h3>Demo</h3>
  <ul class="clean-list">
    <li>Your robot is evaluated on its ability to perform a task.</li>
    <li>The evaluation includes an <strong>oral exam</strong> &mdash; individual questions on how the robot works.</li>
    <li>Demos are graded <strong>all-or-nothing</strong>, with extra credit available for excellent proficiency.</li>
    <li>Four <strong>Demo Days</strong> and one <strong>Race Day</strong>. Fail a task &mdash; retry on the next Demo Day.</li>
    <li>You may attempt the oral exam <strong>only once</strong>, on the same day as your first successful demo.</li>
  </ul>

  <h3>Report</h3>
  <ul class="clean-list">
    <li>A cumulative report describing the methods used to solve the robot tasks.</li>
    <li>Due at the <strong>end of the semester</strong>.</li>
    <li>Submitted <strong>individually</strong> &mdash; evaluation criteria shared in advance.</li>
  </ul>
</section>

<section id="presentation" class="syllabus-section">
  <h2>Research presentation</h2>
  <p>Each student presents one assigned paper to the class. Dates are randomized and may shift with lecture pacing &mdash; the date listed is the <em>earliest</em> you might be called on.</p>

  <h3>Format (~20 minutes)</h3>
  <p>Prepare a brief, open-ended presentation that supports class discussion. Good things to include:</p>
  <ul class="clean-list">
    <li>What problem does the paper address?</li>
    <li>What are the paper's contributions?</li>
    <li>What methods are used?</li>
    <li>What results are achieved?</li>
    <li>How does the work fit into a larger robotics research arc?</li>
    <li>What future work do the authors propose &mdash; and what are the gaps or limitations?</li>
    <li>What questions does the paper leave you with?</li>
  </ul>

  <h3>Tutorial component</h3>
  <p>While reading, keep a list of unfamiliar robotics terms or concepts (things that are fundamental beyond just this paper). Pick one and give a <strong>3&ndash;5 slide tutorial</strong> on it as part of your presentation.</p>

  <h3>Questions</h3>
  <p>Submit <strong>2 questions with solutions</strong> to Prof. Greer by email. Any format (multiple choice, short answer, true/false). At least one should relate to your tutorial concept.</p>
</section>

<section id="exams" class="syllabus-section">
  <h2>Exams</h2>
  <h3>Midterms (2)</h3>
  <ul class="clean-list">
    <li>In-class, in-person &mdash; <strong>no alternates, no exceptions</strong>.</li>
    <li>Your <strong>highest midterm replaces your lowest</strong> &mdash; a built-in free pass if you have to miss one.</li>
  </ul>

  <h3>Final exam</h3>
  <ul class="clean-list">
    <li>In-person, no alternate times.</li>
    <li>If you have a known conflict (religious observance, official UC event), report it <strong>before the first midterm</strong>.</li>
  </ul>
</section>

<section id="policies" class="syllabus-section">
  <h2>Policies</h2>

  <details class="policy">
    <summary><strong>Academic integrity</strong></summary>
    <p>Academic honesty is taken very seriously at UC Merced. <strong>Talk to each other about concepts &mdash; that's how you learn.</strong> But when it's time to turn in a solution, write it yourself.</p>
    <p>Not allowed:</p>
    <ul>
      <li>Sharing or receiving solutions before, during, or after the semester.</li>
      <li>Submitting a friend's work to test the autograder.</li>
      <li>Examining someone else's solution for "ideas."</li>
      <li>Submitting ChatGPT / GitHub Copilot output as your own solution.</li>
      <li>Posting course solutions or materials publicly.</li>
      <li>Code obfuscation to dodge detection.</li>
    </ul>
    <p><strong>Penalties:</strong> first offense &rarr; the negative of the assignment's maximum points (and it cannot be dropped). Second offense &rarr; automatic F in the course. All cases are reported to the Office of Student Rights and Responsibilities.</p>
  </details>

  <details class="policy">
    <summary><strong>Participation bonus</strong></summary>
    <p>Up to <strong>2.5%</strong> added to your grade for active engagement in Piazza, lab, and lecture.</p>
    <p>Good participation looks like:</p>
    <ul>
      <li>Public Piazza posts (private when posting unreleased solutions).</li>
      <li>Searching before posting to avoid duplicates.</li>
      <li>Asking specific, detailed questions.</li>
      <li>Using the quality vote buttons instead of "+1" replies.</li>
    </ul>
    <p>Please do not expect staff to debug your code &mdash; show us you've written a test, isolated the failure, and stepped through it, and we can help you find the bug.</p>
    <p>Filming, photographing, or recording class is not allowed &mdash; it keeps the classroom safe for everyone to ask questions.</p>
  </details>

  <details class="policy">
    <summary><strong>Inclusion &amp; classroom climate</strong></summary>
    <p>You belong here. We welcome students from every background, identity, and path. If your name or pronouns differ from official records, let us know &mdash; we'll use what you prefer. If a religious holiday conflicts with an exam, tell us early and we'll work it out.</p>
    <p>If something about the classroom environment isn't working for you, bring it to us directly or by email. We can't fix what we don't hear about.</p>
  </details>

  <details class="policy">
    <summary><strong>Extenuating circumstances</strong></summary>
    <p>Circumstances outside your control &mdash; health crises, family emergencies, technical disasters &mdash; can qualify for extra support. <strong>Tell us early.</strong> The more lead time we have, the more options we have.</p>
  </details>

  <details class="policy">
    <summary><strong>Campus resources</strong></summary>
    <ul>
      <li><strong>Counseling and Psychological Services</strong> &mdash; mental health support.</li>
      <li><strong>Office for Prevention of Harassment and Discrimination</strong> &mdash; for survivors of sexual violence.</li>
      <li><strong>988 Suicide &amp; Crisis Lifeline</strong> &mdash; call or text 988.</li>
      <li><strong>Technology Resources Program</strong> &mdash; laptop and technology support.</li>
      <li><strong>Dean of Students</strong> &mdash; (209) 228-3633.</li>
      <li><strong>Student Accessibility Services</strong> &mdash; (209) 228-6996, <a href="mailto:access@ucmerced.edu">access@ucmerced.edu</a>.</li>
    </ul>
  </details>
</section>

<section id="resources" class="syllabus-section">
  <h2>Books &amp; resources</h2>

  <p class="muted">No official textbook &mdash; but reading around the topics is one of the best ways to learn the material. Any of the books below will serve you well; exams are written from course concepts, not textbook trivia.</p>

  <h3>Robotics</h3>
  <ul class="clean-list">
    <li><em>State Estimation for Robotics</em> &mdash; Barfoot</li>
    <li><em>Probabilistic Robotics</em> &mdash; Thrun, Burgard &amp; Fox</li>
    <li><em>Bayesian Filtering and Smoothing</em> &mdash; S&auml;rkk&auml;</li>
  </ul>

  <h3>Computer vision</h3>
  <ul class="clean-list">
    <li><em>Computer Vision: Algorithms and Applications</em> &mdash; Szeliski (<a href="https://szeliski.org/Book/" target="_blank" rel="noopener">free online</a>)</li>
    <li><em>Introductory Techniques for 3D Computer Vision</em> &mdash; Trucco &amp; Verri</li>
    <li><em>Computer Vision: A Modern Approach</em> &mdash; Forsyth &amp; Ponce</li>
    <li><em>Digital Image Processing</em> &mdash; Gonzalez &amp; Woods</li>
    <li><em>Multiple View Geometry</em> &mdash; Hartley &amp; Zisserman</li>
    <li><em>An Invitation to 3D Vision</em> &mdash; Ma, Soatto, Kosecka, Sastry</li>
  </ul>

  <h3>Supplemental</h3>
  <ul class="clean-list">
    <li><em><a href="https://www.routledge.com/Deep-and-Shallow-Machine-Learning-in-Music-and-Audio/Dubnov-Greer/p/book/9781032133911">Deep and Shallow: Machine Learning in Music and Audio</a></em> &mdash; Dubnov &amp; Greer</li>
    <li>Research papers on FCN, U-Net, R-CNN, Edge Boxes, YOLO, Vision Transformers, contrastive learning (N-pair loss, CPC, ConVIRT), CLIP, Fourier features, Segment Anything.</li>
    <li>Visual odometry &amp; SLAM: RANSAC-based stereo VO, StereoScan, eight-point algorithm, dense RGB-D SLAM, direct sparse odometry, five-point relative pose.</li>
    <li><a href="https://www.3blue1brown.com/topics/neural-networks" target="_blank" rel="noopener">3Blue1Brown neural network series</a></li>
  </ul>
</section>

<section id="faq" class="syllabus-section">
  <h2>FAQ</h2>
  <p class="muted">Click a question to expand.</p>

  <details class="faq"><summary>How do I get help when I'm stuck?</summary><p>Post on Piazza first &mdash; classmates and staff respond there, and your question probably helps others too. Come to office hours (Prof. Greer: Mon 12:00&ndash;12:30 PM, SE2 209, or by appointment). Email is for private matters.</p></details>

  <details class="faq"><summary>Can I use ChatGPT or Copilot?</summary><p>Not as a solution generator. Pasting AI output as your assignment answer counts as an academic integrity violation. Using AI to learn concepts or debug your own code is fine &mdash; the line is what you submit.</p></details>

  <details class="faq"><summary>What if I fail a demo?</summary><p>You get to try again on the next Demo Day. Just remember: you can attempt the oral exam <strong>only once</strong>, and it must be taken on the same day as your first successful demo.</p></details>

  <details class="faq"><summary>What if I miss a midterm?</summary><p>There are no make-up midterms. The good news: your highest midterm replaces your lowest, so missing one is effectively your "drop." If something serious happens, contact Prof. Greer right away.</p></details>

  <details class="faq"><summary>What if I have a conflict with the final exam?</summary><p>Report it <strong>before the first midterm</strong> so we can plan ahead. There are no alternate times unless your conflict was reported and approved early.</p></details>

  <details class="faq"><summary>Can I collaborate with classmates?</summary><p>You can &mdash; and should &mdash; discuss concepts with other students. But you must write your own solutions and reports in your own words. If you can't explain it to me on the spot, you don't own the solution yet.</p></details>

  <details class="faq"><summary>Do I have to come to lecture / lab?</summary><p>Attendance isn't graded, but the lab is where your robot lives. Show up. Bonus participation points reward active engagement.</p></details>

  <details class="faq"><summary>I need accommodations. What do I do?</summary><p>Contact Student Accessibility Services ((209) 228-6996, <a href="mailto:access@ucmerced.edu">access@ucmerced.edu</a>) and forward your accommodation letter to Prof. Greer. Reach out as early as possible so we can make sure everything is in place.</p></details>

  <details class="faq"><summary>I'm worried about my grade. Now what?</summary><p>Come talk to us early &mdash; don't wait until week 14. Office hours exist for this. We can talk through study strategies, point you to resources, and help you figure out where the gap is.</p></details>

  <details class="faq"><summary>Can I record lectures?</summary><p>No filming, photographing, or audio recording of lectures without permission. If you need a recording for accessibility reasons, work through Student Accessibility Services.</p></details>
</section>
