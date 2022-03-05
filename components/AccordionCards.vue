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
          <b-card-text style="font-family: 'Champange'; font-size: 18px">
            The first limited collection of unique 10,000 NFT tokens, a Union of
            Female Robbers and heist specialists inside the ultimate MetaVerse
            governed by the THG (The Heist Group)
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
          >What is the supply and mint price?</b-button
        >
      </b-card-header>
      <b-collapse id="accordion-2" accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text style="font-family: 'Champange'; font-size: 18px"
            >There will be a total of 10,000 The Heist identities available for
            a mint price of 0.05 ETH + gas fees</b-card-text
          >
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
          <b-card-text style="font-family: 'Champange'; font-size: 18px">
            THG tokens will be available for purchase only on our official
            website and on OpenSea.
            <!-- <p>
              1. Sign up for Metamask or Coinbase Wallet and download the
              extension on your internet browser.
            </p>

            <p>
              2. Make sure you have enough Ethereum in your wallet to cover the
              total cost including gas fees.
            </p>

            <p>
              3. On mint day, there will be a Connect button at the top of our
              website to connect to your wallet.
            </p>

            <p>
              4. Click on the mint button and you will be prompted to sign for
              your transaction. There will be a fee associated with every
              transaction related to gas prices.
            </p>

            <p>
              5. Once you have made your purchase, your WonderPals NFTs will
              appear in your wallet and on Opensea!
            </p> -->
          </b-card-text>
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
          >What is the Utility?</b-button
        >
      </b-card-header>
      <b-collapse id="accordion-4" accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text style="font-family: 'Champange'; font-size: 18px"
            >Holders of The Heist identities will gain access to our amazing
            community, exclusive merch, giveaways of 1/1 art pieces and gain
            priority in future collections.</b-card-text
          >
        </b-card-body>
      </b-collapse>
    </b-card>

    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button
          style="font-family: 'abys'"
          block
          v-b-toggle.accordion-5
          variant="secondary"
          >What is an NFT?</b-button
        >
      </b-card-header>
      <b-collapse id="accordion-5" accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text style="font-family: 'Champange'; font-size: 18px"
            >NFT stands for “non-fungible token” which are unique digital items
            that are stored and encrypted on the blockchain that people can buy,
            own, and trade. NFTs can simply be digital art but can have various
            benefits. They can be treated like membership cards where holders
            get exclusive access to things like websites, events, merchandise,
            and more.</b-card-text
          >
        </b-card-body>
      </b-collapse>
    </b-card>
  </div>
</template>
