<template>
  <div>
    <div class="sp-container">
      <sp-sign-in />
      <sp-bank-balances />
      <sp-token-send />
    <poll-form />
    <poll-list/>
    </div>
  </div>
</template>

<script>
import * as sp from "@tendermint/vue";
import PollForm from "../components/PollForm";
import PollList from "../components/PollList";

export default {
  components: { ...sp, PollForm, PollList },
};
</script>
