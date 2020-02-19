<template>
  <div class="container">
    <h1>Get the latest tech news</h1>
    <section class="featured-posts">
      <ul>
        <PostPreview 
          id="1"
          title="Lorem ipsum dolor amet"
          previewText="Lorem ipsum dolor amet bitters pok pok flannel, health goth single-origin coffee yuccie man bun occupy beard food truck waistcoat irony marfa."
          contentText="Lorem ipsum dolor amet bitters pok pok flannel, health goth single-origin coffee yuccie man bun occupy beard food truck waistcoat irony marfa. Bespoke PBR&B drinking vinegar pop-up umami four dollar toast synth whatever locavore cardigan humblebrag occupy roof party pitchfork. Blue bottle pork belly tote bag keffiyeh chambray. Farm-to-table etsy banh mi enamel pin keytar, vexillologist butcher 8-bit shaman cronut hexagon vinyl brunch XOXO. Post-ironic paleo tacos, plaid live-edge leggings ethical. Everyday carry copper mug DIY succulents, flannel 90's knausgaard selvage echo park readymade seitan. Tacos gluten-free irony meh, activated charcoal tote bag master cleanse copper mug fingerstache PBR&B fixie."
        />
        <PostPreview 
          id="2"
          title="Lorem ipsum dolor amet"
          previewText="Lorem ipsum dolor amet bitters pok pok flannel, health goth single-origin coffee yuccie man bun occupy beard food truck waistcoat irony marfa."
          contentText="Lorem ipsum dolor amet bitters pok pok flannel, health goth single-origin coffee yuccie man bun occupy beard food truck waistcoat irony marfa. Bespoke PBR&B drinking vinegar pop-up umami four dollar toast synth whatever locavore cardigan humblebrag occupy roof party pitchfork. Blue bottle pork belly tote bag keffiyeh chambray. Farm-to-table etsy banh mi enamel pin keytar, vexillologist butcher 8-bit shaman cronut hexagon vinyl brunch XOXO. Post-ironic paleo tacos, plaid live-edge leggings ethical. Everyday carry copper mug DIY succulents, flannel 90's knausgaard selvage echo park readymade seitan. Tacos gluten-free irony meh, activated charcoal tote bag master cleanse copper mug fingerstache PBR&B fixie."
        />
    </ul>
    </section>
  </div>
</template>

<script>
import PostPreview from '~/components/PostPreview'
export default {
  components: {
    PostPreview
  }
}
</script>