<template>
  <div id="app">
    <div>
      <header>
        <li>WordPress</li>
        <li>Websites</li>
        <li>Blogs</li>
        <li>Features</li>
        <li>Pricing</li>
        <li>News</li>
        <li>Support</li>
        <div>
          <li>Log In</li>
          <li>Get Started</li>
        </div>

      </header>
    </div>
    <div>
    <h1>{{ msg }}</h1>
    <h2>Join the global community.</h2>
    <h3>WordPress.com is the easiest place to get started.</h3>
    <h3>Get a custom domain, tons of features, and 24/7 expert support from $4.00/ mo.</h3>
    <button>Get Started</button><br><a href="#">See Plans</a>
    <h3>Self-hosted WordPress optiosn: hosts | Jetpack plugin</h3>
    </div>
    <span>Business plans now offer access to thousands of WordPress plugins and themes!</span>
    <div>
      <h1>Start with a domain</h1>
      <h3>Find the domain name that defines you and your next big idea.</h3>
      <h3>Grab a domain now even if it's not quite time to start a site.</h3>
      <h3>Your domain will be ready when you are.</h3>
      <button>Find your domain</button>
      <br>
      <input type="text" />
    </div>
    <div>
      <div>
        <h1>Design your success story with a powerful website</h1>
        <h3>Every website starts with an idea. WordPress.com provides the design, features, and support to bring it to life. 
          Choose your theme, pick a domain, select a plan, and start building your future.</h3>
          <button>Build a website</button>
          <a href="#">Learn More</a>
      </div>
      <div>
        <h1>Create your blog and share your voice</h1>
        <h3>Plug into the biggest community of publishers online. WordPress has millions of users waiting to find you.
          All the features you need and more. Choose the most popular blogging software on the web for your online home.
        </h3>
          <button>Start a blog</button>
          <a href="#">Learn More</a>
      </div>
      <div>
        <div>
        <h1>Make a website that's your own</h1>
        <h3>Choose from more than 350 easy-to-use themes for any type of business, portfolio, or blog.</h3>
        <button>Browse themes</button>
        </div>
        <div>Images will go here</div>
      </div>
      <div>
        <div>
          <h1>Your look</h1>
          <h3>Impress your visitors with an elegant and unique site. Choose fonts, colors, and add your logo and custom
            CSS to make your website your own.
          </h3>
        </div>
        <div>
          <image />
        </div>
        <div>
          <h1>Your media</h1>
          <h3>Display your media in sophisticated galleries and upload tons of photos, videos, and documents with our
             generous file storage.</h3>
        </div>
        <div>
          <image />
        </div>
      </div>
      <div>
      <div>
        <h1>Create everywhere and anywhere</h1>
        <h3>Start a website on your mobile phone and update it seamlessly from any device. Choose from a wide
          selection of responsive themes that look great everywhere.
        </h3>
      </div>
      <div>
        <image/>
      </div>
      </div>
      <div>
        <div>
          <h1>Build an audience</h1>
          <h3>Use our social media syndication, sharing buttons, SEO tools, and insightful site statistics
            to increase your traffic and monitor your growth. Start with $200 in ad credits, on us.
          </h3>
          <h1>A secure website you can count on</h1>
          <h3>Your site will always be available, secure, and automatically backed up. Anti-spam protection is built into every
            WordPress.com site.
          </h3>
        </div>
        <div>
          <h1>Find help whenever you need it</h1>
          <h3>Get support from our experts 24/7 through email or live chat. Connect with a community of users through forums,
            guided courses, and events around the world.
          </h3>
          <h1>Do more with features</h1>
          <h3>Add extra features to your site like advanced galleries, forms, and email subscriptions, polls, sophisticated
            comments, and much more.
          </h3>
        </div>
      </div>
      <div>
        <div>
          <h2>"Refocusing our business meant an extensive rebrand and rename. WordPress.com made it easy to implement the changes we
          needed for a social media first impression."</h2>
          <h3>-Jeri</h3>
        </div>
        <div>
          <h2>"I just can't keep myself away from WordPress. It has had such a positive influence on my life since I started
            becoming an active member of the community."</h2>
          <h3>-Britta</h3>
        </div>
      </div>
      <div>
        <h1>Versatile plans and pricing</h1>
        <h2>Free</h2>
        <h6>for life</h6>        
        <h2>Personal</h2>
        <h6>per month, billed yearly</h6>
        <h2>Premium</h2>
        <h6>per month, billed yearly</h6>
        <h2>Business</h2>
        <h6>per month, billed yearly</h6>
        <span>COMPARE PLANS</span>
        <div>
          <h3>Discover what your website can do with more power</h3>
          <button>Get Started</button>
        </div>
      </div>
      <div>
        <h4>OTHER WORDPRESS SOLUTIONS</h4>
        <ul>
          <li>Jetpack plugin</li>
          <li>Woocommerce</li>
          <li>Pressable (managed hosting)</li>
          <li>VIP (enterprise hosting)</li>
          <li>Developers</li>
        </ul>
        <h4>EXPLORE</h4>
        <ul>
          <li>News</li>
          <li>Discover</li>
          <li>Go: Growth Content</li>
          <li>Desktop Apps</li>
          <li>Mobile Apps</li>
        </ul>
        <h4>COMMUNITY</h4>
        <ul>
          <li>Support</li>
          <li>Forums</li>
          <li>WordCamps</li>
          <li>WordPress.org</li>
        </ul>
        <h4>COMPANY</h4>
        <ul>
          <li>About Us</li>
          <li>Privacy</li>
          <li>Terms of Service</li>
          <li>Matt Mullenweg</li>
        </ul>
        <h6>Automattic is hiring backend developers anywhere in the world. Join us!</h6>
        <h5>An AUTOMATTIC contraption</h5>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      msg: "WordPress powers 29% of the internet"
    };
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1,
h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
