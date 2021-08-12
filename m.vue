<template>
    <div class="portal-component__input-option-group">

        <div class="at__header">
            {{ label }}
        </div>

        <div class="at__body">
            <slot></slot>
        </div>
    </div>
</template>

<script>

    export default {

        props: {

            label: {
                type: String
            }

        },

        data() {

            return {};

        }

    }

</script>
