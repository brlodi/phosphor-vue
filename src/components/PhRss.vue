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
      <path
        d="M47.99414,144a64,64,0,0,1,64,64"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M47.99414,96a112,112,0,0,1,112,112"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M47.99414,48a160,160,0,0,1,160,160"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <circle cx="52" cy="204" r="16" />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <path
        d="M47.99414,144a64,64,0,0,1,64,64"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M47.99414,96a112,112,0,0,1,112,112"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M47.99414,48a160,160,0,0,1,160,160"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <circle cx="52" cy="204" r="12" />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M98.90576,157.08752a71.531,71.531,0,0,1,21.08838,50.91211,8,8,0,0,1-16,0,56.00027,56.00027,0,0,0-56-56,8,8,0,1,1,0-16A71.53147,71.53147,0,0,1,98.90576,157.08752ZM47.99414,87.99963a8,8,0,1,0,0,16,104.00183,104.00183,0,0,1,104,104,8,8,0,0,0,16,0,120.00093,120.00093,0,0,0-120-120Zm118.794,1.20606A166.90561,166.90561,0,0,0,47.99414,39.99963a8,8,0,0,0,0,16,151.00491,151.00491,0,0,1,107.48047,44.52051,151.00328,151.00328,0,0,1,44.51953,107.47949,8,8,0,0,0,16,0A166.90191,166.90191,0,0,0,166.78809,89.20569ZM51.99414,191.99963a12,12,0,1,0,12,12A12.01344,12.01344,0,0,0,51.99414,191.99963Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <path
        d="M47.99414,144a64,64,0,0,1,64,64"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M47.99414,96a112,112,0,0,1,112,112"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M47.99414,48a160,160,0,0,1,160,160"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <circle cx="52" cy="204" r="10" />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <path
        d="M47.99414,144a64,64,0,0,1,64,64"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M47.99414,96a112,112,0,0,1,112,112"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M47.99414,48a160,160,0,0,1,160,160"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <circle cx="52" cy="204" r="8" />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <path
        d="M48,144a64,64,0,0,1,64,64"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M48,96A112,112,0,0,1,160,208"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M48,48A160,160,0,0,1,208,208"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <circle cx="52" cy="204" r="12" />
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
  name: "PhRss",
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
