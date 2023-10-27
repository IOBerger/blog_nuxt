
export default Vue.component('Post', {
    props: {
        id: number,
        date: Date,
        title: string,
        text: string
    }
});

<template>
    <div class="post"><div><b>{{ title }}</b></div><div><small><i>{{ date }}</i></small></div><div>{{ text }}</div></div>
</template>
