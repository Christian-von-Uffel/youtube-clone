<template>
    <div class="grid grid-cols-4 gap-4 bg-black text-white px-4">
        <div v-for="video in videos" :key="video.id" class="mb-6">
            <!-- image preview -->
            <div class="h-40 bg-gray-500 mb-3"></div>
            <div class="flex gap-3 pointer-cursor">
                <!-- channel image -->
                <div class="rounded-full h-8 w-8 bg-gray-500 overflow-hidden"></div>
                <div class="text-sm">
                    <div class="font-medium">
                        video title
                    </div>
                    <div class="text-gray-400">
                        channel name
                    </div>
                    <div class="text-gray-400">
                        view count * time since video was published
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            videos: [
                {
                    title: "",
                    previewImage: "",
                    views: "",
                    link: "",
                    date: "",
                },
                {
                    title: "",
                    previewImage: "",
                    views: "",
                    link: "",
                    date: "",
                },
                {
                    title: "",
                    previewImage: "",
                    views: "",
                    link: "",
                    date: "",
                },
                {
                    title: "",
                    previewImage: "",
                    views: "",
                    link: "",
                    date: "",
                },
                {
                    title: "",
                    previewImage: "",
                    views: "",
                    link: "",
                    date: "",
                },
                {
                    title: "",
                    previewImage: "",
                    views: "",
                    link: "",
                    date: "",
                },
                {
                    title: "",
                    previewImage: "",
                    views: "",
                    link: "",
                    date: "",
                },
                {
                    title: "",
                    previewImage: "",
                    views: "",
                    link: "",
                    date: "",
                },
                {
                    title: "",
                    previewImage: "",
                    views: "",
                    link: "",
                    date: "",
                },
                {
                    title: "",
                    previewImage: "",
                    views: "",
                    link: "",
                    date: "",
                },
            ]
        }
    }
}
</script>