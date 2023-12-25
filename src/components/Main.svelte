<script>
    import Step from "./Step.svelte";

    let steps = [
        {
            name: "Self-Driving Car",
            icon: "fa-solid fa-car",
            description:
                "Developed an advanced Self-Driving Car model using Deep Q-Learning, integrating sensor and orientation inputs. Implemented with PyTorch for neural networks and Kivy for interactive visuals, showcasing the fusion of cutting-edge AI technologies in autonomous vehicles. Explore the future of transportation through our innovative project.",
            link: "https://github.com/adityarao225/mlproject"
        },
        {
            name: "Credit-Card-Default",
            icon: "fa-solid fa-credit-card",
            description:
                "Engineered payment default prediction models utilizing logistic regression, SVM, and XGBoost. Executed comprehensive data preprocessing and feature engineering in Python for enhanced accuracy, offering valuable insights for risk assessment and financial decision-making.",
            link: "https://github.com/adityarao225/mlproject"
        },  
        {
            name: "Anime-Face-Generator",
            icon: "fa-solid fa-theater-masks",
            description:
                "Augment your datasets with our filters and dataset manipulations to ensure your models are trained on the highest quality datasets (coming soon).",

            link: "https://github.com/adityarao225/Anime-Face-Generator"
        },
        {
            name: "Sales-Insights-Power BI",
            icon: "fa-solid fa-chart-bar",
            description:
                "Augment your datasets with our filters and dataset manipulations to ensure your models are trained on the highest quality datasets (coming soon).",

            link: "https://app.powerbi.com/view?r=eyJrIjoiYzBlZDg2YWItMTJlNi00NzA2LWI3N2UtNzk4NGU3MzI2MDExIiwidCI6IjlkZGFhY2ExLTM4OWYtNGNiMS1hMTEzLTA4MWJlNmNjMjVmYyIsImMiOjZ9"
        },
    ];

    let benefits = [
        {
            metric: "10x",
            name: "Education",
            description:
                "I aim to showcase my passion and expertise in Electrical and Computer Engineering, with a strong focus on machine learning and deep learning. With a Master's degree from the University of Southern California and a Bachelor's degree from Veermata Jijabai Technological Institute, I have honed my skills in areas such as human activity recognition using LSTM models, autonomous self-driving car development and stock price prediction through NLP and time series forecasting.",
        },
        {
            name: "Goals",
            description:
                "My hands-on experience implementing cutting-edge technologies and leading collaborative projects underscores my commitment to innovation. I am eager to connect with fellow professionals, engage in meaningful discussions, and explore opportunities to leverage my technical skills and contribute to the ever-evolving landscape of engineering and artificial intelligence.",
        },
        {
            name: "Skills",
            description:
                "Communication is key and it's a paramount value of mine. I believe in transparency and constructive communication above all else. This helps me develop deep relationships and ensures my effectiveness and productivity in any work space with any team. I am proficient in a diverse set of programming languages including Python, C++, HTML, CSS, and JavaScript. My technical skills encompass Machine Learning, AWS, Deep Learning, Data Structures and Algorithms, Statistics, Azure, and Linux. I am adept at utilizing frameworks such as Tensorflow, Pytorch, Numpy, Pandas, Seaborn, OpenCV, MongoDB, SQL, Flask, and Python scripting, with troubleshooting expertise. I am familiar with various tools like Visual Studio Code, Pycharm, Google Colab, Jupyter Notebooks, Tableau, Kafka, Docker, Power BI, Excel, and Microsoft Office.",
        },
    ];
</script>

<main class="flex flex-col flex-1 p-4">
    <section
        id="introPage"
        class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14"
    >
        <div
            class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
        >
            <h2 class="font-semibold text-4xl sm:text-5xl md:text-5xl">
                Hi! I'm <span class="poppins text-violet-400">Aditya</span> Rao
                <br />Machine Learning <span class="poppins text-violet-400">Engineer</span>
            </h2>
            <p class="text-base sm:text-lg md:text-xl">
                My <span class="text-violet-400"> interests</span> includes Machine Learning, Deep Learning, Data Science, and Software Development!
            </p>
            <button class="blueShadow mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950">
                <a href="Resume/resume.pdf" target="_blank">
                    <div class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200" />
                    <h4 class="relative z-9">Download Resume &rarr;</h4>
                </a>
            </button>
            
            
        </div>
        <div class="relative shadow-2xl grid place-items-center">
            <img
                src={"images/profile.png"}
                alt="Zetane Engine"
                class="object-cover z-[2] max-h-[70vh]"
            />
        </div>
        <!-- <div  class="flex p-0.5 relative max-w-[700px] w-full mx-auto">
            <div
                class="absolute inset-0 overflow-hidden rounded-md flex items-center justify-center"
            >
                <div
                    class="bg-gradient-to-r absolute inset-[-20px]  from-violet-800 to-indigo-800 specialSpin"
                />
            </div>

            <img
                src={"images/zetane-engine.jpeg"}
                alt="Zetane Engine"
                class="w-full h-full object-cover z-[2]"
            />
        </div> -->
    </section>
    <section class="py-20 lg:py-32 flex flex-col gap-24" id="projects">
        <div class="flex flex-col gap-2 text-center">
            <h6 class="text-large sm:text-xl md:text-2xl">
                A few of my creative endeavors.
            </h6>
            <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
                Curious to <span class="poppins text-violet-400">see</span> my work?
            </h3>
        </div>
        <a
            href="https://drive.google.com/file/d/1H4XvkTNcWScp6wDrbG5PC82JacVhBhRU/view?usp=sharing"
            target="_blank"
            class="mx-auto px-4 py-2 rounded-md border border-solid border-white flex items-center gap-2 -mb-4 sm:-mb-0 -mt-10 hover:border-violet-700 duration-200"
        >
            <i class="fa-regular fa-circle-play" />
            <p>Watch the video</p>
        </a>
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
            <Step step={steps[0]}>
                <p>
                    Embark on a visionary journey with our pioneering Self-Driving Car model. Intricately crafted through the application of <strong class="text-violet-400">Deep Q-Learning</strong>, it seamlessly incorporates sensor and orientation inputs. This cutting-edge project is fueled by PyTorch for neural networks and Kivy for interactive visuals, presenting a harmonious fusion of state-of-the-art AI technologies that shape the future of autonomous vehicles.

                </p>
            </Step>
            <Step step={steps[1]}>
                <p>

                    Engineered payment default prediction models utilizing <strong class="text-violet-400"> logistic regression, SVM, and XGBoost</strong>. Executed comprehensive data preprocessing and feature engineering in Python for enhanced accuracy, offering valuable insights for risk assessment and financial decision-making.
                </p>
            </Step>
            
            <Step step={steps[2]}>
                <p>
                    Created lifelike anime faces with exceptional detail using a  <strong class="text-violet-400">PyTorch-based DCGAN</strong>. Deployed in a Streamlit web app for interactive anime face generation, including loss curve visualizations for model performance insights.
                </p>
            </Step>

        </div>
        <div class="grid grid-cols-1 gap-12">
            <Step step={steps[3]}>
                <style>
                    @media screen and (max-width: 1100px) {
                        /* Apply styles for screens with a maximum width of 767px (e.g., mobile devices) */
                        iframe {
                            width: 125%;
                            height: 300px; /* Adjust the height as needed for mobile */
                        }
                    }
                </style>
                
                <section class="py-10 lg:py-16 flex flex-col gap-16 sm:gap-20 md:gap-24 text-center">
                    <div class="mx-auto">
                        <iframe title="Power BI Project" width="1000" height="673.5" src="https://app.powerbi.com/view?r=eyJrIjoiYzBlZDg2YWItMTJlNi00NzA2LWI3N2UtNzk4NGU3MzI2MDExIiwidCI6IjlkZGFhY2ExLTM4OWYtNGNiMS1hMTEzLTA4MWJlNmNjMjVmYyIsImMiOjZ9" frameborder="0" allowFullScreen="true"></iframe>
                    </div>
                </section>
                <p>
                    Through this project, I successfully addressed the complex challenges faced by the computer hardware business. The Power BI dashboard I created empowered the Sales Director with timely and actionable insights, enabling the company to navigate the ever-changing market landscape effectively. This project is a testament to my commitment to excellence in data analysis and my proficiency in utilizing <strong class="text-violet-400"> SQL and Power BI </strong> as essential tools in the pursuit of data-driven solutions.
                </p>
            </Step>
            
        </div>
    </section>
    <!-- <section class="py-10 lg:py-16 flex flex-col gap-16 sm:gap-20 md:gap-24 text-center">
        <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
            Power BI Project
        </h3>
        <div class="mx-auto">
            <iframe title="Power BI Project" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiYzBlZDg2YWItMTJlNi00NzA2LWI3N2UtNzk4NGU3MzI2MDExIiwidCI6IjlkZGFhY2ExLTM4OWYtNGNiMS1hMTEzLTA4MWJlNmNjMjVmYyIsImMiOjZ9" frameborder="0" allowFullScreen="true"></iframe>
        </div>
    </section> -->
    <section
        id="about"
        class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
    >
        <!-- <div class="z-[-1] bg-violet-950 w-screen left-1/2 -translate-x-1/2 top-0 h-full absolute"> </div> -->
        <div
            class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-violet-700 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-violet-700 py-4"
        >
            <h6 class="text-large sm:text-xl md:text-2xl">
                Want to know more?
            </h6>
            <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
                A bit <span class="poppins text-violet-400">about</span> me.
            </h3>
        </div>
        <p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
            My . . .
        </p>
        <div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
            {#each benefits as benefit, index}
                <!-- <div class="flex flex-col gap-2 mx-auto">
                    <div class="flex items-end gap-4">
                        <p
                            class="poppins text-6xl sm:text-7xl md:text-8xl text-slate-500 font-medium"
                        >
                            {benefit.metric}
                        </p>
                        <p
                            class="text-xl sm:text-2xl md:text-3xl capitalize pb-2"
                        >
                            {benefit.name}
                        </p>
                    </div>
                    <p class="text-center italic">- {benefit.description}</p>
                </div> -->
                <div class="flex gap-6 sm:gap-8">
                    <p
                        class="poppins text-4xl sm:text-5xl md:text-6xl text-slate-500 font-semibold"
                    >
                        0{index + 1}
                    </p>
                    <div class="flex flex-col gap-6 sm:gap-8">
                        <h3 class="text-2xl sm:text-3xl md:text-5xl">
                            {benefit.name}
                        </h3>
                        <p>{benefit.description}</p>
                    </div>
                </div>
            {/each}
        </div>

        <h5 class={" text-2xl sm:text-3xl font-semibold text-center poppins "}>
            The <span class="text-violet-400">Complete</span> Package
        </h5>
        <div
            class="flex flex-col overflow-x-scroll gap-10 max-w-[800px] mx-auto w-full"
        >
            <table class="bg-white text-slate-700 rounded text-center">
                <thead class={"border-b border-solid border-slate-200  "}>
                    <tr class="">
                        <th />
                        <th class="whitespace-nowrap p-2 px-4">Candidate #1</th>
                        <th class="whitespace-nowrap p-2 px-4">Candidate #2</th>
                        <th class="whitespace-nowrap p-2 px-4">Candidate #3</th>
                        <th
                            class="bg-red-700 text-white whitespace-nowrap p-4 px-8"
                            >Me</th
                        >
                    </tr>
                </thead>
                <tbody>
                    <tr class="border-b border-solid border-slate-200">
                        <td
                            class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                            >Dedication</td
                        >
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-green-500" /></td>
                    </tr>
                    <tr class="border-b border-solid border-slate-200">
                        <td
                            class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                            >Critical Thought</td
                        >
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-green-500" /></td>
                    </tr>
                    <tr>
                        <td
                            class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                            >Interpersonal Skills</td
                        >
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-green-500" /></td>
                    </tr>
                    <tr class="border-t border-solid border-slate-200">
                        <td
                            class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                            >Progamming Ability</td
                        >
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-green-500" /></td>
                    </tr>
                </tbody>
            </table>
        </div>

        <div class="mx-auto -mt-12 italic sm:hidden opacity-50">
            <p>Scroll to see more &rarr;</p>
        </div>
        <p class="mx-auto">So why not invest?</p>
    </section>
</main>