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
      <rect
        x="31.99995"
        y="48.00781"
        width="192"
        height="160"
        rx="8"
        transform="translate(256.00777 0.00786) rotate(90)"
        stroke-width="24"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <line
        x1="92"
        y1="76"
        x2="164"
        y2="76"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <circle cx="104" cy="128" r="16" />
      <circle cx="152" cy="128" r="16" />
      <circle cx="104" cy="176" r="16" />
      <circle cx="152" cy="176" r="16" />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <rect x="80" y="64" width="96" height="48" opacity="0.2" />
      <rect
        x="80"
        y="64"
        width="96"
        height="48"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="31.99995"
        y="48.00781"
        width="192"
        height="160"
        rx="8"
        transform="translate(256.00777 0.00786) rotate(90)"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <circle cx="88" cy="148" r="12" />
      <circle cx="128" cy="148" r="12" />
      <circle cx="168" cy="148" r="12" />
      <circle cx="88" cy="188" r="12" />
      <circle cx="128" cy="188" r="12" />
      <circle cx="168" cy="188" r="12" />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M200,24.00781H56a16.01833,16.01833,0,0,0-16,16v176a16.01833,16.01833,0,0,0,16,16H200a16.01833,16.01833,0,0,0,16-16v-176A16.01833,16.01833,0,0,0,200,24.00781ZM88,200a12,12,0,1,1,12-12A12.01375,12.01375,0,0,1,88,200Zm0-40a12,12,0,1,1,12-12A12.01375,12.01375,0,0,1,88,160Zm40,40a12,12,0,1,1,12-12A12.01375,12.01375,0,0,1,128,200Zm0-40a12,12,0,1,1,12-12A12.01375,12.01375,0,0,1,128,160Zm40,40a12,12,0,1,1,12-12A12.01375,12.01375,0,0,1,168,200Zm0-40a12,12,0,1,1,12-12A12.01375,12.01375,0,0,1,168,160Zm16-56a7.99977,7.99977,0,0,1-8,8H80a7.99977,7.99977,0,0,1-8-8V64a7.99977,7.99977,0,0,1,8-8h96a7.99977,7.99977,0,0,1,8,8Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <rect
        x="80"
        y="64"
        width="96"
        height="48"
        stroke-width="12"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="31.99995"
        y="48.00781"
        width="192"
        height="160"
        rx="8"
        transform="translate(256.00777 0.00786) rotate(90)"
        stroke-width="12"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <circle cx="88" cy="148" r="10" />
      <circle cx="128" cy="148" r="10" />
      <circle cx="168" cy="148" r="10" />
      <circle cx="88" cy="188" r="10" />
      <circle cx="128" cy="188" r="10" />
      <circle cx="168" cy="188" r="10" />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <rect
        x="80"
        y="64"
        width="96"
        height="48"
        stroke-width="8"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="31.99995"
        y="48.00781"
        width="192"
        height="160"
        rx="8"
        transform="translate(256.00777 0.00786) rotate(90)"
        stroke-width="8"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <circle cx="88" cy="148" r="8" />
      <circle cx="128" cy="148" r="8" />
      <circle cx="168" cy="148" r="8" />
      <circle cx="88" cy="188" r="8" />
      <circle cx="128" cy="188" r="8" />
      <circle cx="168" cy="188" r="8" />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <rect
        x="80"
        y="64"
        width="96"
        height="48"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="31.99995"
        y="48.00781"
        width="192"
        height="160"
        rx="8"
        transform="translate(256.00777 0.00786) rotate(90)"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <circle cx="88" cy="148" r="12" />
      <circle cx="128" cy="148" r="12" />
      <circle cx="168" cy="148" r="12" />
      <circle cx="88" cy="188" r="12" />
      <circle cx="128" cy="188" r="12" />
      <circle cx="168" cy="188" r="12" />
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
  name: "PhCalculator",
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
