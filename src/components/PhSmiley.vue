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
        r="96"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M169.57812,151.99627a48.02731,48.02731,0,0,1-83.15624.00073"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <circle cx="92" cy="108" r="16" />
      <circle cx="164" cy="108" r="16" />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <circle cx="128" cy="128" r="96" opacity="0.2" />
      <circle
        cx="128"
        cy="128"
        r="96"
        fill="none"
        :stroke="displayColor"
        stroke-miterlimit="10"
        stroke-width="16"
      />
      <path
        d="M169.57812,151.99627a48.02731,48.02731,0,0,1-83.15624.00073"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <circle cx="92" cy="108" r="12" />
      <circle cx="164" cy="108" r="12" />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M128,24A104,104,0,1,0,232,128,104.12041,104.12041,0,0,0,128,24Zm36,72a12,12,0,1,1-12,12A12.0006,12.0006,0,0,1,164,96ZM92,96a12,12,0,1,1-12,12A12.0006,12.0006,0,0,1,92,96Zm84.5,60.00781a56.20543,56.20543,0,0,1-26.6875,23.58594A56.0807,56.0807,0,0,1,79.5,156.00781a7.99843,7.99843,0,1,1,13.84375-8.01562,40.274,40.274,0,0,0,19.09375,16.86719,40.44532,40.44532,0,0,0,31.14062,0,40.0058,40.0058,0,0,0,12.70313-8.57813,40.82317,40.82317,0,0,0,6.375-8.28906A7.99843,7.99843,0,1,1,176.5,156.00781Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <circle
        cx="128"
        cy="128"
        r="96"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M169.57812,151.99627a48.02731,48.02731,0,0,1-83.15624.00073"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <circle cx="92" cy="108" r="10" />
      <circle cx="164" cy="108" r="10" />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <circle
        cx="128"
        cy="128"
        r="96"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M169.57812,151.99627a48.02731,48.02731,0,0,1-83.15624.00073"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <circle cx="92" cy="108" r="8" />
      <circle cx="164" cy="108" r="8" />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <circle
        cx="128"
        cy="128"
        r="96"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M169.57812,151.99627a48.02731,48.02731,0,0,1-83.15624.00073"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <circle cx="92" cy="108" r="12" />
      <circle cx="164" cy="108" r="12" />
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
  name: "PhSmiley",
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
