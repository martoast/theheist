<template>
  <div class="accordion" role="tablist">
    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button
          style="font-family: 'abys'"
          block
          v-b-toggle.accordion-1
          variant="secondary"
          >What is The Heist?</b-button
        >
      </b-card-header>
      <b-collapse
        id="accordion-1"
        visible
        accordion="my-accordion"
        role="tabpanel"
      >
        <b-card-body>
          <b-card-text>
            <p style="font-family: 'Champange'">
              The first limited collection of unique 10,000 NFT tokens, a Union
              of Female Robbers and heist specialists inside the ultimate
              MetaVerse governed by the THG (The Heist Group)
            </p>
          </b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>

    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button
          style="font-family: 'abys'"
          block
          v-b-toggle.accordion-2
          variant="secondary"
          >How much does an Identity cost?</b-button
        >
      </b-card-header>
      <b-collapse id="accordion-2" accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text>0.05 ETH + gas.</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>

    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button
          style="font-family: 'abys'"
          block
          v-b-toggle.accordion-3
          variant="secondary"
          >How can I get a Heist Identity?</b-button
        >
      </b-card-header>
      <b-collapse id="accordion-3" accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text
            >THG tokens will be available for purchase on our official website
            as well as secondary marketplaces like OpenSea.</b-card-text
          >
        </b-card-body>
      </b-collapse>
    </b-card>

    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button
          style="font-family: 'abys'"
          block
          v-b-toggle.accordion-4
          variant="secondary"
          >Where can I find more information?</b-button
        >
      </b-card-header>
      <b-collapse id="accordion-4" accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text
            >Join our free discord channel to learn more and interact with
            members of the community.</b-card-text
          >
        </b-card-body>
      </b-collapse>
    </b-card>
  </div>
</template>
