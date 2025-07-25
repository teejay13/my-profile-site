<script>
    import SectionWrapper from "./SectionWrapper.svelte";
    import ProfilePic from "$lib/TJ2024.jpg"
</script>

<SectionWrapper>
    <div class="mx-auto mt-12 grid grid-cols-1 md:grid-cols-10 gap-12 items-start">
        <!-- Left column: Text content -->
        <div class="md:col-span-7">
            <h1 class="text-4xl font-extrabold mb-2">Hello, I'm Abdulhaq "Teejay" Salako</h1>
            <h2 class="text-xl font-semibold text-gray-700 mb-6">
            I'm an PhD student studying visualization and visual analytics
            </h2>
            <p class="text-gray-800 mb-3">
            I currently work with 
            <a href="https://vca.informatik.uni-rostock.de/~ct/" class="text-blue-600 underline">Christian Tominski</a> in the 
            <a href="https://vca.informatik.uni-rostock.de/en/" class="text-blue-600 underline">Institute for Visual & Analytic Computing</a>. 
            My research focuses on improving <span class="font-semibold">human-AI alignment</span> by designing systems that reveal model representations and methods to shift them toward human expectations.
            </p>
            <p class="text-gray-800 mb-3">
            Previously, I graduated with my SB and MEng in Computer Science from MIT, where I worked with 
            <a href="#" class="text-blue-600 underline">Jim Glass</a> and 
            <a href="#" class="text-blue-600 underline">David Harwath</a> in the 
            <a href="#" class="text-blue-600 underline">Spoken Language Systems Group</a>.
            Throughout my PhD, I have been fortunate to spend summers as a research intern at 
            <a href="#" class="text-blue-600 underline">Apple</a> with 
            <a href="#" class="text-blue-600 underline">Fred Hohman</a> and at IBM Research with 
            <a href="#" class="text-blue-600 underline">Hendrik Strobelt</a>.
            </p>
            <p class="text-gray-800 mb-5">
            I am honored to have had my research supported by the MIT John Jarve Fellowship and the 
            <a href="#" class="text-blue-600 underline">Apple Scholars in AI/ML PhD Fellowship</a>.
            </p>
            <!-- Contact Row -->
            <div class="flex items-center gap-3 mt-4 flex-wrap">
            
            </div>
        </div>

        <!-- Right column: Image -->
        <div class="md:col-span-3 flex">
            <img
            src={ProfilePic}
            alt="Teejay Salako"
            class="rounded-xl object-cover"
            />

        </div>
    </div>
</SectionWrapper>

