<template>
   <div style="background-color: #000 !important">
      <div class="d-none d-md-block" style="position: absolute; right: 3.5rem; top:2.5rem; z-index: 100">
         <b-btn class="p-0" href="//twitter.com/theheistworld" variant="link">
            <img style="width: 2rem;" class="mx-2" src="/twitterlogo.svg"></img>
         </b-btn>
         <b-btn class="p-0" href="//discord.com/invite/theheistworld" variant="link">
            <img style="width: 3rem;" class="mx-1" src="/OPENSEA.svg"></img>
         </b-btn>
         <b-btn class="p-0" href="//opensea.io/collection/the-heist-collection" variant="link">
            <img style="max-width: 3rem;" class="mx-2" src="/opensea2.svg"></img>
         </b-btn>
         <b-btn class="p-0" href="//etherscan.io/address/0xcF8009F8E3446296d02B63d43E8066D130ce27B3" variant="link">
            <img style="max-width: 2rem;" class="mx-2" src="/etherscan-logo.svg"></img>
         </b-btn>
         
      </div>
     

      <div class="d-none d-md-block">
         <video id="vid" ref="vid" width="100%" height="100%" autoplay playsinline muted loop>
         <source src="/MotelBig.mp4" type="video/mp4">
         <div class="d-none d-md-block" style="position: fixed; right: 49%; bottom: 3.5rem; z-index: 100">
            <img style="max-width: 3rem;" src="/scrollhelp.gif"></img>
         </div>
         
      </video>

      </div>

      <div class="d-block d-md-none">
         <video id="vid" ref="vid" width="100%" height="100%" autoplay playsinline muted loop>
         <source src="/MotelSmall.mp4" type="video/mp4">
         <div class="d-block d-md-none" style="position: fixed; right: 42%; bottom: 2.5rem; z-index: 100">
            <img style="max-width: 3rem;" src="/scrollhelp.gif"></img>
         </div>
         
      </video>

      </div>

      

      
      

      
      
      <b-container class="text-white text-center py-5" >
         
         <b-row align-h="center"  align-v="center" no-gutters>
            <b-col class="py-5" md="4" cols="12">
               
               <b-row  no-gutters>
                     <b-col>
                        <b-btn  class="p-0"  variant="link">
                     <img style="max-width: 40%;"  class="mx-2" src="/Gas-Tank.png"></img>
                  </b-btn>
                        <div style="font-family: 'Market'; font-size: 28px;" class="font-weight-bold text-gray">100% Hand Drawn Layers</div>
                        <div style="font-family: 'Champange'; font-size: 22px;">Created and drawn by a female artist.</div>
                     </b-col>
                  </b-row>
            </b-col>
            <b-col class="py-5" md="4" cols="12">
               <div style="align-items: center; justify-content: center;">
                 
                  <b-row  no-gutters>
                     <b-col>
                        <b-btn class="p-0" variant="link">
                     <img style="max-width: 50%;" class="mx-2" src="/popcorn.png"></img>
                  </b-btn>
                        <div style="font-family: 'Market'; font-size: 28px;" class="font-weight-bold text-gray">Every Identity Is Unique</div>
                        <div style="font-family: 'Champange'; font-size: 22px;">Created from a combination of 100+ distinct traits with varying rarity.</div>
                     </b-col>
                  </b-row>
               </div>
            </b-col>
            <b-col class="py-5" md="4" cols="12">
               <div style="align-items: center; justify-content: center;">
                  
                  <b-row  no-gutters>
                     <b-col>
                        <b-btn class="p-0 m-0"  variant="link">
                           <img style="max-width: 50%;" class="mx-2" src="/keys.png"></img>
                        </b-btn>
                        <div style="font-family: 'Market'; font-size: 28px;">Member Only Access</div>
                        <div style="font-family: 'Champange'; font-size: 22px;">Gain access to exclusive merch, auctions, giveaways, and more!</div>
                     </b-col>
                  </b-row>
               </div>
            </b-col>
         </b-row>
      </b-container>
      <b-container class="py-5">
         <h2 class="text-center text-white py-3" style="font-family: 'Market'; font-size: 42px;">The Gallery</h2>
         <div>
            <b-card-group class="d-none d-md-block" columns>
               <b-card
                  img-src="/images/gallery/7818.png"
                  img-alt="Image"
                  class="border-0"
                  overlay
                  ></b-card>
               <b-card
                  img-src="/images/gallery/7846.png"
                  img-alt="Image"
                  class="border-0"
                  overlay
                  ></b-card>
               <b-card
                  img-src="/images/gallery/7812.png"
                  img-alt="Image"
                  class="border-0"
                  overlay
                  ></b-card>
               <b-card
                  img-src="/images/gallery/5211.png"
                  img-alt="Image"
                  class="border-0"
                  overlay
                  ></b-card>
               <b-card
                  img-src="/images/gallery/8061.png"
                  img-alt="Image"
                  class="border-0"
                  overlay
                  ></b-card>
               <b-card
                  img-src="/images/gallery/4741.png"
                  img-alt="Image"
                  class="border-0"
                  overlay
                  ></b-card>
               <b-card
                  img-src="/rocketgirl.jpeg"
                  img-alt="Image"
                  class="border-0"
                  overlay
                  ></b-card>
               <b-card
                  img-src="/images/gallery/1356.png"
                  img-alt="Image"
                  class="border-0"
                  overlay
                  ></b-card>
               <b-card
                  img-src="/images/gallery/88.png"
                  img-alt="Image"
                  class="border-0"
                  overlay
                  ></b-card>
               
               
               
            </b-card-group>
            <div class="d-block d-md-none">
               <b-carousel
      id="carousel-1"
      :interval="4000"
     
      controls
      img-width="1024"
      img-height="480"      
    >
   
      <b-carousel-slide img-src="/images/gallery/5406.png"></b-carousel-slide>
      <b-carousel-slide img-src="/images/gallery/7818.png"></b-carousel-slide>
      <b-carousel-slide img-src="/images/gallery/5812.png"></b-carousel-slide>
      <b-carousel-slide img-src="/images/gallery/1356.png"></b-carousel-slide>
      <b-carousel-slide img-src="/images/gallery/7812.png"></b-carousel-slide>
      <b-carousel-slide img-src="/images/gallery/0.jpeg"></b-carousel-slide>
      <b-carousel-slide img-src="/images/gallery/7779.png"></b-carousel-slide>
      <b-carousel-slide img-src="/images/gallery/5211.png"></b-carousel-slide>
      <b-carousel-slide img-src="/images/gallery/88.png"></b-carousel-slide>
      

    </b-carousel>

            </div>
            
         </div>
      </b-container>
      <b-container fluid class="py-3 py-md-5  text-white text-center">
         <b-row align-v="center">
            <b-col  cols="12" md="6" sm="12">
               <div class="d-none d-md-block">
                  <h2 class="text-center" style="font-family: 'Market'; font-size: 42px;">About the Artist</h2>
               </div>
               <div class="d-block d-md-none">
                  <h2 class="text-center" style="font-family: 'Market'; font-size: 38px;">About the Artist</h2>
               </div>
               <p style="font-family: 'Champange'; font-size: 22px" class="px-2 px-md-5">
                  The Artist, Melanie Mercado has been developing this story, this universe for over 5 years. The original story and illustrations were done with markers and in the form of a comic book, recounting personal stories and fictional stories brought to life (and provoked) by real events. The Heist women are Alter Ego portraits turned, Calendar, turned comic book turned - THE ULTIMATE - NFT Collection.
               </p>
               <p style="font-family: 'Champange'; font-size: 22px" class="px-2 px-md-5">
                  These identities are an extension of herself as an individual, her experiences, rage, happiness, fantasies, her evolution as an artist and as a woman. Carrying the struggles of what women have to deal with and the power that comes with it and from it. 
               </p>
               <p style="font-family: 'Champange'; font-size: 22px" class="px-2 px-md-5">Welcome to The Heist.</p>
               <p class="px-5">
                  <img class="px-5" style="height: 38px" src="/Mel-Signature.svg" />
               </p>
            </b-col>
            <b-col cols="12" md="6" sm="12">
                  <b-card
                  img-src="/webmel.jpg"
                  img-alt="Image"
                  class="border-0"
                  style="max-width:40rem;"
                  
                  overlay
                  ></b-card>
            </b-col>
         </b-row>
      </b-container>

      <b-container fluid class="d-none d-md-block py-5 px-0 px-md-5 text-white">
         <b-row align-v="center">
            <b-col  cols="12" md="6" sm="12">
               <b-card
                  img-src="/gasstation.jpg"
                  img-alt="Image"
                  class="border-0"
                  overlay
                  ></b-card>
            </b-col>
            <b-col class="py-5"  cols="12" md="6" sm="12">
               <h2 class="text-center py-3" style="font-family: 'Market'; font-size: 42px;">The Heist story</h2>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  The Heist Group consists of 3 women who find themselves at a crossroad. A drunk and impulsive night turned into risking everything they have and moving across the country in an attempt to change their lives. Little did they know how much their lives would actually change. Between terrible decisions and awful money management they find themselves having to choose between options.. Continuing down the straight and narrow path, or getting into a life of crime. The choice is made for them when they accidentally (but almost by choice) kill a friend’s A$$hole boyfriend. After this horrific incident- there is no turning back.
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                 They start to plot and scheme their way into New York, robbing several gas stations and eventually a bank on the way.
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  The papers… ugh… the papers! They never seem to get it right. Some say that they wear masks because they are hiding something, others say they wear wigs and a bare face. OH! The horror- for who would believe 3 gorgeous 20 year old women would cause such a ruckus.
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  They breeze through the small towns unnoticed and uncaptured. Leaving nothing behind but a trail of empty cash registers and male bank tellers who piss their pants.
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  Once they arrive in New York they lay low, they try to get normal jobs and do normal things. But let's be honest- once you get a taste of the pie, you can never say no. And their stomachs are hungry, more hungry for bigger and better things, FASTER!- I mean, isn’t that what New York does to everyone?
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  They hit Atlantic City to hide all of the money they've collected… This is where The Heist Group was born.
A committee of all women that broke free from the rules of society, from poverty, and the strict laws of their Government.
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  They created a union of 10,000 ruthless female trained escape artists, specialized in Heist Missions against this system. Spectators seem to only catch but a glimpse of the crimes they commit. Sly, prestigious but executing their plans precisely.
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  Some say that thousands of them are all dressed in different attire when seen in person, others think it is the same 3 girls doing it all. Legend has it, by the time the local authorities are to be contacted for help, a cloud of dust is seen out of the building. Some have ideas of what they look like, and others say it is all a myth. Not only are these women professional bank robbers, jewelry thieves, and hijackers on a block chain, they plan to expand inside of the METAVERSE. 
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  It is believed they run the largest Crime Union on the Western Hemisphere called The Heist Group and they are looking for expansion! 
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                 But like they say in the Papers- “It may all just be a myth”...
               </p>
            </b-col>
         </b-row>
      </b-container>

      <b-container fluid class="d-block d-md-none py-5 px-0 px-md-5 text-white">
         <b-row align-v="center">
            <b-col class="py-5"  cols="12" md="6" sm="12">
               <h2 class="text-center py-3" style="font-family: 'Market'; font-size: 42px;">The Heist story</h2>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  The Heist Group consists of 3 women who find themselves at a crossroad. A drunk and impulsive night turned into risking everything they have and moving across the country in an attempt to change their lives. Little did they know how much their lives would actually change. Between terrible decisions and awful money management they find themselves having to choose between options.. Continuing down the straight and narrow path, or getting into a life of crime. The choice is made for them when they accidentally (but almost by choice) kill a friend’s A$$hole boyfriend. After this horrific incident- there is no turning back.
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                 They start to plot and scheme their way into New York, robbing several gas stations and eventually a bank on the way.
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  The papers… ugh… the papers! They never seem to get it right. Some say that they wear masks because they are hiding something, others say they wear wigs and a bare face. OH! The horror- for who would believe 3 gorgeous 20 year old women would cause such a ruckus.
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  They breeze through the small towns unnoticed and uncaptured. Leaving nothing behind but a trail of empty cash registers and male bank tellers who piss their pants.
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  Once they arrive in New York they lay low, they try to get normal jobs and do normal things. But let's be honest- once you get a taste of the pie, you can never say no. And their stomachs are hungry, more hungry for bigger and better things, FASTER!- I mean, isn’t that what New York does to everyone?
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  They hit Atlantic City to hide all of the money they've collected… This is where The Heist Group was born.
A committee of all women that broke free from the rules of society, from poverty, and the strict laws of their Government.
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  They created a union of 10,000 ruthless female trained escape artists, specialized in Heist Missions against this system. Spectators seem to only catch but a glimpse of the crimes they commit. Sly, prestigious but executing their plans precisely.
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  Some say that thousands of them are all dressed in different attire when seen in person, others think it is the same 3 girls doing it all. Legend has it, by the time the local authorities are to be contacted for help, a cloud of dust is seen out of the building. Some have ideas of what they look like, and others say it is all a myth. Not only are these women professional bank robbers, jewelry thieves, and hijackers on a block chain, they plan to expand inside of the METAVERSE. 
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                  It is believed they run the largest Crime Union on the Western Hemisphere called The Heist Group and they are looking for expansion! 
               </p>
               <p style="font-family: 'Champange';" class="px-2 px-md-3">
                 But like they say in the Papers- “It may all just be a myth”...
               </p>
            </b-col>
            <b-col  cols="12" md="6" sm="12">
               <b-card
                  img-src="/gasstation.jpg"
                  img-alt="Image"
                  class="border-0"
                  overlay
                  ></b-card>
            </b-col>
            
         </b-row>
      </b-container>

      <b-container class="py-5">
         <h2 class="text-center text-white py-3" style="font-family: 'Market'; font-size: 42px;">Meet the Team</h2>
         <meet-team></meet-team>

      </b-container>

      <b-row no-gutters class="d-none d-md-block" style="height: 100vh; background-image: url('/clean_background.png');  background-repeat: no-repeat;
         background-size: cover;">

         <b-col>
            <b-row style="height:100vh" align-h="center" align-v="center" align-content="center">
               <b-col cols="4">
                  <h2 class="text-center text-white pb-2" style="font-family: 'Market'; font-size: 42px;">Q & A</h2>
                <accordion-cards></accordion-cards>

               </b-col>
            </b-row>
            
               
            
         </b-col>
         
      </b-row>



       <b-container class="d-block d-md-none" style="padding-top:2.5rem; padding-bottom:13rem">
         <b-row align-v="center" style="height: 55vh">
            <b-col  cols="12" md="6" sm="12">
              <h2 class="text-center text-white pb-2" style="font-family: 'Market'; font-size: 42px;">Q & A</h2>
                <accordion-cards></accordion-cards>
            </b-col>
            <b-col cols="12" md="6" sm="12">
               <div class="d-none d-md-block" style="padding-top:2.5rem; padding-bottom:2.5rem;">
                  <b-img src="/MINTING-BUTTON (1).jpg" fluid alt="Responsive image"></b-img>
               </div>
            </b-col>
         </b-row>
      </b-container>

     
      <b-container fluid class="bg-white text-center">
         <b-row class="p-4" align-v="center" align-h="center">
            <b-col cols="12" md="auto" sm="12" class="mr-auto p-3 px-md-5">
               <div class="d-block d-md-none py-3">
                  <b-btn class="p-0" href="//twitter.com/theheistworld" variant="link">
                     <img style="width: 2rem;" class="mx-2" src="/mobile/twittermobile.svg"></img>
                  </b-btn>
                  <b-btn class="p-0" href="//discord.com/invite/theheistworld" variant="link">
                     <img style="width: 3rem;" class="mx-1" src="/mobile/discordmobile.svg"></img>
                  </b-btn>
                  <b-btn class="p-0" href="//opensea.io/collection/the-heist-collection" variant="link">
                     <img style="max-width: 3rem;" class="mx-2" src="/mobile/openseamobile.svg"></img>
                  </b-btn>
                  <b-btn class="p-0" href="//etherscan.io/address/0xcF8009F8E3446296d02B63d43E8066D130ce27B3" variant="link">
                     <img style="max-width: 2rem;" class="mx-2" src="/mobile/etherscanmobile.svg"></img>
                  </b-btn>
               </div>
               <div class="terms" style="text-decoration: underline">
                  <b-btn style="font-size: large; text-decoration: underline;" v-b-modal.modal-terms variant="link" class="text-dark"
                     >THE HEIST TERMS & CONDITIONS</b-btn
                     >
               </div>
               <div class="terms text-danger">2022 THE HEIST ™</div>
            </b-col>
            <b-col cols="12" md="auto" sm="12" class="ml-auto "
               ><img style="height: 54px" src="/Mel-Signature.svg"
               />
                
               
            </b-col>
         </b-row>
      </b-container>

      <b-modal body-bg-variant="dark" size="lg" header-bg-variant="dark" header-close-variant="danger" header-border-variant="dark"  id="modal-terms" centered hide-footer>
         <b-container fluid>
          <h1 class="title text-white text-center">TERMS & CONDITIONS</h1>
          <div class="about text-white pt-2 pt-md-4">
        <p>
          The Heist is a collection of digital artworks (NFTs) running on the
          Ethereum network. This website is only an interface allowing
          participants to exchange digital collectibles. Users are entirely
          responsible for the safety and management of their own private
          Ethereum wallets and validating all transactions and contracts
          generated by this website before approval. Furthermore, as The Heist
          smart contract runs on the Ethereum network, there is no ability to
          undo, reverse, or restore any transactions.
        </p>
        <p>
          This website and its connected services are provided “as is” and “as
          available” without warranty of any kind. By using this website you are
          accepting sole responsibility for any and all transactions involving
          The Heist digital collectibles.
        </p>
        <h1 class="title text-center">OWNERSHIP</h1>
        <ol type="I">
          <li>
            You Own the NFT. Each Identity* is an NFT on the Ethereum
            blockchain. When you purchase an NFT, you own the underlying
            Identity*, the Art, completely. Ownership of the NFT is mediated
            entirely by the Smart Contract and the Ethereum Network: at no point
            may we seize, freeze, or otherwise modify the ownership of any
            Identity*.
          </li>
          <li>
            Personal Use. Subject to your continued compliance with these Terms,
            The Heist LLC grants you a worldwide, royalty-free license to use,
            copy, and display the purchased Art, along with any extensions that
            you choose to create or use, solely for the following purposes: (i)
            for your own personal, non-commercial use; (ii) as part of a
            marketplace that permits the purchase and sale of your Identity* /
            NFT, provided that the marketplace cryptographically verifies each
            Heist Identity* owner’s rights to display the Art for their Heist
            Identity* to ensure that only the actual owner can display the Art;
            or (iii) as part of a third party website or application that
            permits the inclusion, involvement, or participation of your
            Identity*, provided that the website/application cryptographically
            verifies each The Heist Identity* owner’s rights to display the Art
            for their Heist Identity* to ensure that only the actual owner can
            display the Art, and provided that the Art is no longer visible once
            the owner of The Heist Identity* leaves the website/application.
          </li>
          <li>
            Other than the rights to the Art, nothing herein gives you any
            rights to any other trademarks or other intellectual property rights
            belonging to The Heist. All of these rights are expressly reserved
            in the name of The Heist LLC.
          </li>
          <li>
            Feedback. You may choose to submit comments, bug reports, ideas or
            other feedback about the Site, including without limitation about
            how to improve the Site (collectively, “Feedback”). By submitting
            any Feedback, you agree that we are free to use such Feedback in any
            way we choose without additional compensation to you and you hereby
            grant us a perpetual, irrevocable, nonexclusive, worldwide license
            to incorporate and use the Feedback for any purpose.
          </li>
        </ol>
        <div class="d-flex">
          <h3 class="font-weight-bold text-danger"><i>Identity</i></h3>
          <p class="ml-3 pt-1">
            is the term we use to describe the female form of your NFT. I mean,
            you have to change your identity before a heist... right?
          </p>
        </div>
      </div>
    
      </b-row>

      
    </b-container>
      </b-modal>
   </div>
</template>
<script>
import AccordionCards from "~/components/AccordionCards.vue"
import MeetTeam from "~/components/MeetTeam.vue"
export default {
  components: {
    AccordionCards,
    MeetTeam
 
  },
   
};
</script>
<style>

@font-face {
  font-family: "Abys";
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url("~assets/fonts/abys-regular.otf") format("truetype");
}

@font-face {
  font-family: "komik";
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url("~assets/fonts/komik.ttf") format("truetype");
}

@font-face {
  font-family: "Champange";
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url("~assets/fonts/Champagne.ttf") format("truetype");
}

@font-face {
  font-family: "Market";
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url("~assets/fonts/Market.ttf") format("truetype");
}

.terms {
    font-family: "Champange";
    font-size: 18px;
  }

.about {
  font-family: "Champange";
  font-size: 22px;
}
.title {
  font-family: "komik";
  font-size: 3rem;
}
.shit {
  padding-top: 2rem;
}

.carousel-control-next,
.carousel-control-prev /*, .carousel-indicators */ {
    filter: invert(100%);
}



</style>
