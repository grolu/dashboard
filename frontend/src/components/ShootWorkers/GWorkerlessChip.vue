<!--
SPDX-FileCopyrightText: 2024 SAP SE or an SAP affiliate company and Gardener contributors

SPDX-License-Identifier: Apache-2.0
-->

<template>
  <v-chip
    size="small"
    class="ma-1"
    variant="tonal"
    color="disabled"
    v-tooltip:top="'This cluster does not have worker groups'"
  >
    workerless
  </v-chip>
</template>

<script setup>
</script>
