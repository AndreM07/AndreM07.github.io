<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Andre Mojica's Personal Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Andre Mojica</h1>
        <p>Aspiring Mechanical Engineer</p>
    </header>

    <nav>
        <ul class="tabs">
            <li class="tab" onclick="openTab(event, 'home')">Home</li>
            <li class="tab" onclick="openTab(event, 'about')">About Me</li>
            <li class="tab" onclick="openTab(event, 'experience')">Work Experience</li>
            <li class="tab" onclick="openTab(event, 'projects')">Engineering Projects</li>
            <li class="tab" onclick="openTab(event, 'courses')">Engineering Courses</li>
            <li class="tab" onclick="openTab(event, 'contact')">Contact</li>
        </ul>
    </nav>

    <div id="home" class="tab-content">
        <h2>Welcome to my personal website!</h2>
        <p>I'm Andre Mojica, an aspiring mechanical engineer with a passion for solving real-world problems. My interests include engineering, finance, and history. Feel free to explore my projects, learn more about my work, or contact me!</p>
    </div>

    <div id="about" class="tab-content">
        <h2>About Me</h2>
        <ul>
            <li>I developed an interest in engineering during my freshman year of high school after taking my first engineering class. This introductory course laid the foundation for my understanding of engineering design.</li>
            <li>I completed 4 years of engineering courses in high school, each focusing on a different branch of engineering, including mechanical, electrical, and coding.</li>
            <li>I am currently pursuing a degree in mechanical engineering at the University of Illinois Chicago.</li>
            <li>Beyond engineering, I have a strong interest in finance. Below is a list of finance books I’ve read:
                <ul>
                    <li><strong>The Buy Side</strong></li>
                    <li><strong>Liar's Poker</strong></li>
                    <li><strong>Den of Thieves</strong></li>
                    <li><strong>A Short History of Financial Euphoria</strong></li>
                    <li><strong>Barbarians at the Gate</strong></li>
                    <li><strong>The Big Short</strong></li>
                    <li><strong>The Predator's Ball</strong></li>
                </ul>
            </li>
        </ul>
    </div>

    <div id="experience" class="tab-content">
        <h2>Work Experience</h2>
        <h3>1. Barista at Starbucks (2019–2021)</h3>
        <ul>
            <li>Started my first job at 16, working as a barista for 2 years.</li>
            <li>Key Responsibilities:
                <ul>
                    <li>Processed customer orders using the POS system.</li>
                    <li>Restocked items at the bar.</li>
                    <li>Prepared and served beverages to customers.</li>
                </ul>
            </li>
            <li>Notable Contribution: During the Covid pandemic, I distributed free coffee to frontline hospital workers.</li>
        </ul>

        <h3>2. Manufacturing at WaterSaver Faucet Co. (May–August 2023)</h3>
        <ul>
            <li>Worked in manufacturing and assembly for 3 months.</li>
            <li>Key Responsibilities:
                <ul>
                    <li>Manufactured and assembled professional laboratory equipment.</li>
                </ul>
            </li>
        </ul>
    </div>

    <div id="projects" class="tab-content">
        <h2>Engineering Projects</h2>
        <h3>1. SAE Wheel Hub Modeling (2024–Present)</h3>
        <ul>
            <li>Description:
                <ul>
                    <li>Collaborating with a group of 5 Senior Design students to design and create an SAE wheel hub.</li>
                    <li>Conducted patent research to explore and brainstorm potential designs.</li>
                    <li>Used SolidWorks to create an original wheel hub design that meets SAE standards.</li>
                    <li>Uploaded the design into ANSYS for Finite Element Analysis (FEA).</li>
                </ul>
            </li>
            <li>Skills Used: ANSYS, Finite Element Analysis, SolidWorks</li>
        </ul>

        <h3>2. Ping Pong Ball Launcher (2022)</h3>
        <ul>
            <li>Description:
                <ul>
                    <li>Worked with a team of four students to design and build an autonomous ping pong ball launcher using Arduino.</li>
                    <li>Utilized SolidWorks to create 3D models for individual components and final prototypes.</li>
                    <li>Created a Gantt chart to prioritize tasks and distribute the work evenly.</li>
                    <li>Built the final design with low-cost materials and presented it at the final competition to peers and faculty.</li>
                </ul>
            </li>
            <li>Skills Used: SolidWorks, Arduino</li>
        </ul>
    </div>

    <div id="courses" class="tab-content">
        <h2>Engineering Courses</h2>
        <h3>Mechanical Vibrations (ME 308)</h3>
        <p>Study of free and forced vibrations in damped linear systems with single and multiple degrees of freedom. Exploration of approximate methods, instrumentation techniques, and practical applications.</p>

        <h3>Fluid Mechanics (ME 211)</h3>
        <p>Examination of fluid properties, dimensional analysis, and the principles of statics and kinematics. Focus on conservation equations, inviscid and incompressible flows, Bernoulli's equation, and integral momentum theorems. Analysis of viscous flows, boundary layer theories, and compressible flows.</p>

        <h3>Heat Transfer (ME 321)</h3>
        <p>Analysis of heat transfer modes, including conduction, convection, and radiation. Study of material properties, extended surfaces, heat exchangers, and shape factors. Hands-on laboratory experiments in conduction, convection, and radiation.</p>

        <h3>Engineering Design (ME 347)</h3>
        <p>Application of conventional and computer-assisted methods for engineering design. Development of geometric manipulation and computer-aided modeling using curves, surfaces, and solids. Integration of finite-element analysis in the design process.</p>
    </div>

    <div id="contact" class="tab-content">
        <h2>Contact</h2>
        <p>Feel free to reach out through the links below:</p>
        <ul>
            <li><a href="https://github.com/AndreM07">My GitHub Profile</a></li>
            <li><a href="mailto:andremojica7@gmail.com">Contact Me</a></li>
        </ul>
    </div>

    <script src="script.js"></script>
</body>
</html>
