<script>
    import SectionWrapper from "./SectionWrapper.svelte";
    import ProfilePic from "$lib/TJ2024.jpg"
</script>

<SectionWrapper>
    <div class="mx-auto mt-12 p-4 sm:p-6 md:p-10 flex flex-col md:flex-row gap-6 items-center">
        <!-- Left column: Text content -->
        <div class="w-full md:w-[70%] text-center order-2 md:order-1 md:text-left space-y-4">
            <h1 class="text-4xl font-bold mb-2">Hello, I'm Abdulhaq "Teejay" Salako</h1>
            <h2 class="text-xl  text-gray-700 mb-6">
            I'm an PhD student studying Human Data Interaction
            </h2>
            <p class="text-gray-800 mb-3">
            I currently work with 
            <a href="https://vca.informatik.uni-rostock.de/~ct/" class="text-blue-600 underline">Christian Tominski</a> in the 
            <a href="https://vca.informatik.uni-rostock.de/en/" class="text-blue-600 underline">Institute for Visual & Analytic Computing</a>. 
            My research focuses on interactive visual metamorphosis for multi-view data exploration. In particular, research emphasizes developing alternative user navigation techniques that enable smooth animated transitions between dedicated visual representations in multi-faceted dataset.
            </p>
            <p class="text-gray-800 mb-3">
            Previously, I graduated with MEng in Computer Science from UESTC China, where I worked with Jiansu Pu and a BSc in Information Technology from Valley View University.
            </p>
            
        </div>

        <!-- Right column: Image -->
        <div class="w-full md:w-[30%] flex flex-col items-center justify-start py-6 order-1 md:order-2">
            <div class="mb-6 md:mb-0 justify-center items-center">
                <img
                    src={ProfilePic}
                    alt="Teejay Salako"
                    class="w-48 h-48 md:w-64 md:h-64 object-cover rounded-full shadow-lg overflow-hidden"
                />
            </div>
            <div class="flex items-center justify-center gap-4 mt-4 flex-wrap">
                <!-- Email -->
                <a href="mailto:your.email@example.com" target="_blank" class="bg-blue-100 rounded-lg p-2 hover:bg-blue-200" title="Email">
                    <!-- Heroicons solid: Envelope -->
                    <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-blue-600" fill="currentColor" viewBox="0 0 20 20">
                    <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/>
                    <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/>
                    </svg>
                </a>
                <!-- LinkedIn -->
                <a href="https://linkedin.com/in/yourprofile" target="_blank" class="bg-blue-100 rounded-lg p-2 hover:bg-blue-200" title="LinkedIn">
                    <!-- Heroicons solid: LinkedIn (use brand svg as Heroicons doesn't include) -->
                    <svg class="w-5 h-5 text-blue-600" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-10h3v10zm-1.5-11.268c-.966 0-1.75-.784-1.75-1.75s.784-1.75 1.75-1.75 1.75.784 1.75 1.75-.784 1.75-1.75 1.75zm13.5 11.268h-3v-5.604c0-1.338-.026-3.062-1.866-3.062-1.868 0-2.154 1.458-2.154 2.965v5.701h-3v-10h2.881v1.367h.041c.401-.761 1.381-1.562 2.844-1.562 3.041 0 3.604 2.002 3.604 4.604v5.591z"/>
                    </svg>
                </a>
                <!-- GitHub -->
                <a href="https://github.com/yourusername" target="_blank" class="bg-blue-100 rounded-lg p-2 hover:bg-blue-200" title="GitHub">
                    <!-- GitHub solid brand icon -->
                    <svg class="w-5 h-5 text-blue-600" fill="currentColor" viewBox="0 0 24 24">
                    <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M12 2C6.477 2 2 6.485 2 12.014c0 4.427 2.865 8.18 6.839 9.504.5.091.682-.217.682-.482 0-.238-.009-.868-.013-1.703-2.782.604-3.37-1.344-3.37-1.344-.454-1.155-1.11-1.463-1.11-1.463-.908-.62.069-.608.069-.608 1.004.07 1.532 1.03 1.532 1.03.892 1.53 2.34 1.09 2.91.832.092-.646.35-1.09.636-1.34-2.22-.254-4.555-1.113-4.555-4.951 0-1.092.39-1.987 1.029-2.688-.103-.254-.446-1.273.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.5.337 1.909-1.295 2.748-1.026 2.748-1.026.546 1.378.202 2.396.1 2.65.64.701 1.028 1.596 1.028 2.688 0 3.848-2.337 4.696-4.566 4.944.36.308.679.92.679 1.855 0 1.338-.012 2.419-.012 2.749 0 .267.18.576.688.479C19.137 20.192 22 16.44 22 12.014 22 6.485 17.523 2 12 2z"/>
                    </svg>
                </a>
                <!-- Resume/CV (PDF) -->
                <a href="/resume.pdf" target="_blank" class="bg-blue-100 rounded-lg p-2 hover:bg-blue-200" title="Resume/CV">
                    <!-- Heroicons solid: Document -->
                    <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-blue-600" fill="currentColor" viewBox="0 0 20 20">
                    <path d="M6 2a2 2 0 00-2 2v12a2 2 0 002 2h8a2 2 0 002-2V8.414a2 2 0 00-.586-1.414l-4.414-4.414A2 2 0 0010.586 2H6zm2 10a1 1 0 102 0 1 1 0 00-2 0zm1-3a1 1 0 100-2 1 1 0 000 2z"/>
                    </svg>
                </a>
            </div>
        </div>
    </div>
    <div class="flex flex-col gap-4">
        <h1 class="text-2xl font-bold text-gray-900">News</h1>
        <div class="flex flex-col gap-2">
            <div class="flex flex-col sm:flex-row sm:items-center gap-1 sm:gap-3">
                <p class="text-sm font-semibold text-gray-500 whitespace-nowrap">April 14, 2025</p>
                <p class="text-base text-gray-800">I will be at CHI in Yokohama 🌸 presenting Abstraction Alignment!</p>
            </div>
            <!-- Add more news items in the same pattern -->
        </div>
    </div>

    <div class="flex flex-col gap-6 mt-10">
        <h1 class="text-2xl font-bold text-gray-900">Featured Publications</h1>
        
        <div class="flex flex-col gap-6">
            <!-- Publication item -->
            <div class="flex flex-col sm:flex-row gap-4 bg-white rounded-xl p-4 shadow-sm">
            <!-- Image (optional, hide on small screens if you wish) -->
            <img src={ProfilePic} alt="Teejay Salako" class="w-42 h-40 object-cover rounded-lg flex-shrink-0 mb-2 sm:mb-0" />
            
            <!-- Publication details -->
            <div class="flex-1 flex flex-col gap-2">
                <div class="text-lg font-semibold text-gray-800">
                Abstraction Alignment: Comparing Model-Learned and Human-Encoded Conceptual Relationships
                </div>
                <div class="text-sm text-gray-600">
                Angie Boggust • Hyemin Bang • Hendrik Strobelt • Arvind Satyanarayan
                </div>
                <div class="text-sm text-blue-700 font-medium">CHI 2025</div>
                <div class="flex flex-wrap gap-3 mt-2">
                <a href="#" class="text-blue-600 bg-blue-50 px-2 py-1 rounded-lg text-xs font-medium hover:underline">Project</a>
                <a href="#" class="text-blue-600 bg-blue-50 px-2 py-1 rounded-lg text-xs font-medium hover:underline">Paper</a>
                <a href="#" class="text-blue-600 bg-blue-50 px-2 py-1 rounded-lg text-xs font-medium hover:underline">Demo</a>
                </div>
            </div>
            </div>

            <!-- Add more publication items below in the same pattern -->

        </div>
    </div>


</SectionWrapper>

