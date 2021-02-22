<template>
  <div id="blogs-page">
    <div class="d-flex justify-content-center blog-header">
      <h1 class="blog-head">BLOG POSTS</h1>
    </div>
    <div class="container page-content">
      <div class="row">
        <div class="col-md-9">
          <div class="blog-title">
            <h2>Will Tech Companies Ever Take Ethics Seriously?</h2>
            <p><Pencil /> Carlo Coste <Calendar /> December 2019</p>
          </div>
          <p class="blog-content text-justify">
            In Evan Selinger’s article Will Tech Companies Ever Take Ethics
            Seriously? published on Medium, he confronts about the importance of
            ethics– the discipline dealing with what is good and bad and with
            moral duty and obligation– in big tech companies for producing
            products and services responsible for possible data exploitation. He
            points out three largest ethics gaps that big tech companies have to
            improve: ethics in design, ethics training and procedures at work,
            and ethics education and policy at school. Ethics in design focuses
            on how the products are ethically made including the platform power
            and implementation of safety and privacy. Ethics training and
            procedures at work involves proper ethics training program for
            employees to exercise ethical decision-making. Ethics education and
            policy at school prepares future professionals to be committed to
            ideal information justice before they go to their first jobs as data
            scientists and engineers.

            <br /><br />After the Facebook-Cambridge Analytica scandal where
            Cambridge Analytica illegally collected millions of Facebook
            personal data for political advertising purposes on 2018, Zuckerberg
            called it a breach of trust and promised to reform Facebook policy.
            Several privacy laws have been enforced through the years by data
            protection authorities, however, data breaches still occur even in
            third-party applications. Because of this, it is suggested to add
            stronger force in implementing such laws. It is a wise idea to act
            upon, but lawmakers and big tech companies only focus on
            implementing rules for data processing and ignore the rest that
            needs to be considered, such as ethics.

            <br /><br />As the world go through the information age, it needs
            good role models who will take a stand to information justice and
            data protection. These role models are expected to have undergone
            good ethics curricula or have learned how to think in novel and
            creative ways in philosophy for thought experiment before finishing
            a degree. Being a good role model in the information age is an early
            process of learning to choose ethical decisions and creating a
            connection between what they preach and what they practice. Good
            role models in the work place make ethically concerned employees and
            advocates for the public good. While ethics are to be taught well on
            future leaders and data scientists and engineers, ethics in big tech
            companies is a dual performance. Big tech companies have to consider
            it more seriously if they want to gain a huge amount of public
            trust. They have to listen to their employees who acknowledges that
            there is a loose approach when it comes to implementing data
            processing and privacy guidelines on their products and services. In
            fact, consumers look forward to big tech companies to produce
            products and services they feel the most secured environment.
          </p>
          <hr />
          <div class="blogposts">
            <div class="blog-title">
              <h2>The Human Skills We Need in an Unpredictable World</h2>
              <p><Pencil /> Carlo Coste <Calendar /> November 2019</p>
            </div>

            <div class="embed-responsive embed-responsive-16by9 iframe">
              <iframe
                width="500"
                height="300"
                class="embed-responsive-item"
                src="https://www.youtube.com/embed/w4OPtFCs_fw"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
              ></iframe>
            </div>
            <p class="blog-content text-justify">
              Margaret Heffernan gave a number of great points on her talk about
              The Human Skills We Need in an Unpredictable World. However, the
              three key insights that hit me the most are: one, efficiency works
              really well when you can predict what exactly are you going to
              need; two, we outsource to machine what we could do ourselves;
              three, what’s left out is everything that can’t be measured, which
              is actually something that counts. Efficiency myth creates
              standardized work for a predictable reality, which raises a
              question to unpredictable ones. The world is an infinite
              collection of possibilities and having to envision all of them to
              create an efficient system to work sounds exhausting to me. The
              world needs the human skills and proper intellect back. We build
              machines to do the things humans can do with their bodies. Instead
              of trying to be better on the skills we already have or
              discovering skills we never thought we have, we are too busy
              discovering and making machines to be better, making us less
              skilled. Dependence in technology is what defines survival now.
              Again, the world is getting worse and it wants its humans to be
              ready on what’s to come. Through the years, we have lost the
              spirit of coalition-building that allows us to make friends and
              build solidarity because we are so focused on building systems
              that might help us in the future. It can’t be measured by
              efficiency but it is something that counts if we are to talk about
              global change. Technology can help, but building a skilled nation
              is a preparation for facing an unpredictable world.

              <br /><br />Truthfully, Heffernan’s points only fed my fear of
              losing humanity in a world where humans are intended to enjoy
              their lifetime together. As a student who might be an electronics
              engineer in the future, I know the chances that the world is going
              to face the technology age where humans are forced to live in
              complete dependence on artificially intelligent machines in order
              to survive. I know what engineers are capable to do with enough
              knowledge and resources, and I’m afraid that this age already lies
              somewhere within their grasp. So as an electronics engineer in the
              Philippines, I would want to put efficiency on the idea of people
              working with people. I would want to see us explore our abilities
              while building relationships with another. I acknowledge that
              people needs an inspiration for change, and if that means changing
              my attitude to be mindful whether in workplace or not, I would be
              grateful to challenge myself. I see efficiency when people work
              together and give better results. I see no waste of time on
              passing on an amount of strength from one person to another
              because strength leads to bravery, and bravery to change. Our
              preparedness to face an unpredictable world is not identified by
              technology but by our own ability to adapt. In order for us to
              adapt, we need to be a little more human and a lot less
              technology-dependent.
            </p>
          </div>
        </div>

        <div class="col-md-3">
          <div class="sidebar">
            <h4>Archives</h4>
            <a href="#">November 2019</a><br />
            <a href="#">December 2019</a>

            <h4>Submit your article!</h4>
            <p>
              You can send your work be featured on our page. Send your articles
              at
              <a href="#">email@address.com</a>!
            </p>
          </div>

          <h4>Follow us:</h4>
          <div class="social-links">
            <a href="https://twitter.com/" target="_blank"> <Twitter /></a>
            <a href="https://www.facebook.com/" target="_blank"><Facebook /></a>
            <a href="https://www.instagram.com/" target="_blank"
              ><Instagram
            /></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Pencil from "vue-material-design-icons/LeadPencil.vue";
import Calendar from "vue-material-design-icons/Calendar.vue";
import Twitter from "vue-material-design-icons/Twitter.vue";
import Facebook from "vue-material-design-icons/Facebook.vue";
import Instagram from "vue-material-design-icons/Instagram.vue";

export default {
  name: "blogs",
  components: {
    Pencil,
    Calendar,
    Twitter,
    Facebook,
    Instagram,
  },
};
</script>

<style scoped>
.blog-header {
  background: linear-gradient(rgba(31, 30, 30, 0.6), rgba(31, 30, 30, 0.6)),
    url(https://images.pexels.com/photos/3861972/pexels-photo-3861972.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940);
  height: 400px;
  background-attachment: fixed;
}

@keyframes compress-title {
  0% {
    letter-spacing: 40px;
    opacity: 0.5;
  }
  100% {
    letter-spacing: 20px;
    opacity: 1;
  }
}
.blog-head {
  color: white;
  font-size: 500%;
  line-height: 400px;
  letter-spacing: 20px;
  animation: 1s ease-out compress-title;
}
.sidebar {
  height: 300px;
}

.social-links .material-design-icon {
  font-size: 200%;
  color: rgb(9, 9, 66);
}

.page-content {
  margin-top: 3%;
}

.iframe {
  margin: 20px 0px;
}
</style>

