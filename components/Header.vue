<template>
    <div class="sticky top-0 bg-gray-800 text-gray-100 px-12">
        <div class="flex items-center justify-between py-3">
            <!-- logo -->
            <img src="Logo.png" alt="logo" class="h-6">
            
            <!-- search bar -->
            <form action="">
                <input type="text" placeholder="Search" class="w-[42vw] bg-black font-light py-1 px-4">
                <button class="bg-gray-700 py-1 px-6 rounded-r-sm">
                    O
                </button>
            </form>

            <div class="flex items-center gap-6">
                <button>
                    <!-- upload icon -->
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="white" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 10l4.553-2.276A1 1 0 0121 8.618v6.764a1 1 0 01-1.447.894L15 14M5 18h8a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v8a2 2 0 002 2z" />
                    </svg>
                </button>
                <button>
                    <!-- apps icon -->
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white" fill="white" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2V6zM14 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V6zM4 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2v-2zM14 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z" />
                    </svg>
                </button>
                <button>
                    <!-- notifications icon -->
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white" fill="white" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9" />
                    </svg>
                </button>
                <button>
                    <img src="/headshot_squoosh.jpeg" alt="profile picture" class="rounded-full h-8 overflow-hidden">
                </button>
            </div>
        </div>
        <div class="flex items-center gap-4 py-2 pb-3">
            <button class="rounded-full text-sm py-1 px-3 bg-white hover:bg-gray-300 text-gray-700 hover:bg-gray-600 border border-gray-500 transition duration-150">
                All
            </button>
            <button v-for="tag in tags" :key="tag.id" class="rounded-full text-sm py-1 px-3 bg-gray-700 hover:bg-gray-600 border border-gray-500 transition duration-150">
                {{tag.title}}
            </button>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            tags: [
                {
                    title: "Olympics",
                    link: "",
                },
                {
                    title: "Bitcoin",
                    link: "",
                },
                {
                    title: "Covid",
                    link: "",
                },
                {
                    title: "Delta",
                    link: "",
                },
                {
                    title: "Memes",
                    link: "",
                },
                {
                    title: "Tailwind CSS",
                    link: "",
                },
                {
                    title: "Beck",
                    link: "",
                },
                {
                    title: "Muse",
                    link: "",
                },
                {
                    title: "400M Hurdles",
                    link: "",
                },
                {
                    title: "Lock Picking Lawyer",
                    link: "",
                },
            ]
        }
    }
}
</script>