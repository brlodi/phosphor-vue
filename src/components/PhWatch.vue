/* GENERATED FILE */
<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 0 256 256"
    :width="displaySize"
    :height="displaySize"
    :fill="displayColor"
    :transform="displayMirrored"
    v-bind="$attrs"
    v-on="$listeners"
  >
    <slot />
    <g v-if="displayWeight === 'bold'">
      <circle
        cx="128"
        cy="128"
        r="72"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <polyline
        points="128 96 128 128 160 128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M88,68.12774l6.95849-45.34129A8,8,0,0,1,102.86591,16h50.26817a8,8,0,0,1,7.90743,6.78646L168,68.128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M88,187.87226l6.95849,45.34129A8,8,0,0,0,102.86591,240h50.26817a8,8,0,0,0,7.90743-6.78646L168,187.872"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <circle cx="128" cy="128" r="72" opacity="0.2" />
      <circle
        cx="128"
        cy="128"
        r="72"
        fill="none"
        :stroke="displayColor"
        stroke-miterlimit="10"
        stroke-width="16"
      />
      <polyline
        points="128 88 128 128 168 128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M88,68.12774l6.80838-37.55481A8,8,0,0,1,102.68007,24h50.63985a8,8,0,0,1,7.87169,6.57294L168,68.128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M88,187.87226l6.80838,37.55481A8,8,0,0,0,102.68007,232h50.63985a8,8,0,0,0,7.87169-6.57294L168,187.872"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M175.29687,63.53107l-6.23339-34.38556A15.99062,15.99062,0,0,0,153.31982,16H102.68018A15.99062,15.99062,0,0,0,86.93652,29.14551l-6.2334,34.38556a79.89661,79.89661,0,0,0,0,128.93786l6.2334,34.38556A15.99062,15.99062,0,0,0,102.68018,240h50.63964a15.99062,15.99062,0,0,0,15.74366-13.14551l6.23339-34.38556a79.8966,79.8966,0,0,0,0-128.93786ZM102.68018,32h50.64013l3.90723,21.55316a79.69216,79.69216,0,0,0-58.45508,0Zm50.63964,192H102.67969l-3.90723-21.55316a79.69216,79.69216,0,0,0,58.45508,0ZM168,136H128a8.00008,8.00008,0,0,1-8-8V88a8,8,0,0,1,16,0v32h32a8,8,0,0,1,0,16Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <circle
        cx="128"
        cy="128"
        r="72"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <polyline
        points="128 88 128 128 168 128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M88,68.12774l6.80838-37.55481A8,8,0,0,1,102.68007,24h50.63985a8,8,0,0,1,7.87169,6.57294L168,68.128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M88,187.87226l6.80838,37.55481A8,8,0,0,0,102.68007,232h50.63985a8,8,0,0,0,7.87169-6.57294L168,187.872"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <circle
        cx="128"
        cy="128"
        r="72"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <polyline
        points="128 88 128 128 168 128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M88,68.12774l6.80838-37.55481A8,8,0,0,1,102.68007,24h50.63985a8,8,0,0,1,7.87169,6.57294L168,68.128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M88,187.87226l6.80838,37.55481A8,8,0,0,0,102.68007,232h50.63985a8,8,0,0,0,7.87169-6.57294L168,187.872"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <circle
        cx="128"
        cy="128"
        r="72"
        fill="none"
        :stroke="displayColor"
        stroke-miterlimit="10"
        stroke-width="16"
      />
      <polyline
        points="128 88 128 128 168 128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M88,68.12774l6.80838-37.55481A8,8,0,0,1,102.68007,24h50.63985a8,8,0,0,1,7.87169,6.57294L168,68.128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M88,187.87226l6.80838,37.55481A8,8,0,0,0,102.68007,232h50.63985a8,8,0,0,0,7.87169-6.57294L168,187.872"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
  </svg>
</template>

<script lang="ts">
import Vue from "vue";
import {
  IconComputed,
  IconProps,
  PropValidator,
  IconContext,
  ContextGetter
} from "@/lib/types";
export default Vue.extend<{}, {}, IconComputed, IconProps>({
  name: "PhWatch",
  props: PropValidator,
  inject: ContextGetter,
  computed: {
    displayWeight() {
      const { weight, contextWeight } = this as IconProps & IconContext;
      return weight ?? contextWeight;
    },
    displaySize() {
      const { size, contextSize } = this as IconProps & IconContext;
      return size ?? contextSize;
    },
    displayColor() {
      const { color, contextColor } = this as IconProps & IconContext;
      return color ?? contextColor;
    },
    displayMirrored() {
      const { mirrored, contextMirrored } = this as IconProps & IconContext;
      return mirrored ?? contextMirrored ? "scale(-1, 1)" : undefined;
    }
  }
});
</script>
