<template>
  <div>
    <Navigation />
    <Header />
    <HomeComponent />
    <Footer />
  </div>
</template>

export default {
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
    };
  },
};
