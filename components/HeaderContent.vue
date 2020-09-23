<template>
    <div class="h-full w-screen">
        <div class="h-screen grid grid-cols-1 md:grid-cols-3">
            <slot name="grid-1"></slot>
            <slot name="grid-2"></slot>
            <slot name="grid-3"></slot>
        </div>
    </div>
</template>
<script>
export default {
    props: {
        imgURL: {
            type: String,
            default:''
        },
        heading1: {
            type: String,
            default: 'Heading Content'
        },
        heading2 : {
            type: String,
            default: 'Heading 2 Content'
        }
    }
}
</script>