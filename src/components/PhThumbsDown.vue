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
        d="M31.99414,48h48a0,0,0,0,1,0,0V152a0,0,0,0,1,0,0h-48a8,8,0,0,1-8-8V56a8,8,0,0,1,8-8Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M79.99414,152l40,80a32,32,0,0,0,32-32V176h61.87549a16,16,0,0,0,15.87644-17.98456l-12-96A16,16,0,0,0,201.86963,48H79.99414"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <path
        d="M31.99414,48h48a0,0,0,0,1,0,0V152a0,0,0,0,1,0,0h-48a8,8,0,0,1-8-8V56a8,8,0,0,1,8-8Z"
        opacity="0.2"
      />
      <path
        d="M31.99414,48h48a0,0,0,0,1,0,0V152a0,0,0,0,1,0,0h-48a8,8,0,0,1-8-8V56a8,8,0,0,1,8-8Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M79.99414,152l40,80a32,32,0,0,0,32-32V176h61.87549a16,16,0,0,0,15.87644-17.98456l-12-96A16,16,0,0,0,201.86963,48H79.99414"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M237.68457,157.02344l-12-96.00049A24.03944,24.03944,0,0,0,201.86914,40H31.99414a16.01833,16.01833,0,0,0-16,16v88a16.01833,16.01833,0,0,0,16,16H75.0498l37.78907,75.57764A7.99869,7.99869,0,0,0,119.99414,240a40.04552,40.04552,0,0,0,40-40V184h53.875a24.00051,24.00051,0,0,0,23.81543-26.97656ZM71.99414,144h-40V56h40Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <path
        d="M31.99414,48h48a0,0,0,0,1,0,0V152a0,0,0,0,1,0,0h-48a8,8,0,0,1-8-8V56A8,8,0,0,1,31.99414,48Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M79.99414,152l40,80a32,32,0,0,0,32-32V176h61.87549a16,16,0,0,0,15.87644-17.98456l-12-96A16,16,0,0,0,201.86963,48H79.99414"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <path
        d="M31.99414,48h48a0,0,0,0,1,0,0V152a0,0,0,0,1,0,0h-48a8,8,0,0,1-8-8V56A8,8,0,0,1,31.99414,48Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M79.99414,152l40,80a32,32,0,0,0,32-32V176h61.87549a16,16,0,0,0,15.87644-17.98456l-12-96A16,16,0,0,0,201.86963,48H79.99414"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <path
        d="M31.99414,48h48a0,0,0,0,1,0,0V152a0,0,0,0,1,0,0h-48a8,8,0,0,1-8-8V56a8,8,0,0,1,8-8Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M79.99414,152l40,80a32,32,0,0,0,32-32V176h61.87549a16,16,0,0,0,15.87644-17.98456l-12-96A16,16,0,0,0,201.86963,48H79.99414"
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
  name: "PhThumbsDown",
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
