# customer-quote-slider
Credibility on the web is absolutely paramount in achieving your digital goals. One of the best ways to establish credibility on your website is to display customer logos which indicate to website visitors what caliber of clients you've worked for. However, there is no context to these logos. The website visitor simply knows that your company provided a product or service for that brand and have no idea if the engagement was a success or failure, nor does the logo provide any statistics to display any success in the engagement.  

In our example, we will teach you how to add a customer quote slider to your website that adds context to your customer roster. Instead of logos, the slider will display actual quotes from customers further establishing your credibility and providing site visitors with specific instances of success that they are more likely to relate to and as a result, engage with your business.

## Tutorial

For detailed instruction's, view Solodev's [Adding a Customer Quote Slider using jQuery](https://www.solodev.com/blog/web-design/adding-a-customer-quote-slider-using-jquery.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/qponurqy/).

## HTML

The customer quote slider contains the following basic HTML markup.

```
<div class="patient-quote flexslider">
  <ul class="slides">
    <li>
      <div class="row">
        <div class="col-md-12">
          <h2 class="quote-title">
            96% of WebCorpCo users see an 18% increase in profits the first year.
          </h2>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-10 col-xs-offset-1 col-md-10 col-md-offset-1 text-center">
          <p>
            "WebCorpCo was able to growth hack my business and now i can use my data on my OWN terms" <span>- Male, 30, Data Scientist</span>
          </p>
        </div>
      </div>
    </li>
    <li>
      <div class="row">
        <div class="col-md-12">
          <h2 class="quote-title">
             96% WebCorpCo users see an 18% increase in profits the first year.
          </h2>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-10 col-xs-offset-1 col-md-10 col-md-offset-1 text-center">
          <p>
            "I love the dashboards. The best. Really. Used to be 1,000 tabs. Now it's just one. Remarkable" <span>- Female, 37, VP, Analytics</span>
          </p>
        </div>
      </div>
    </li>
    <li>
      <div class="row">
        <div class="col-md-12">
          <h2 class="quote-title">
             96% WebCorpCo users see an 18% increase in profits the first year.
          </h2>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-10 col-xs-offset-1 col-md-10 col-md-offset-1 text-center">
          <p>
            "For us, WebCorpCo was a revelation. So this is how I can use Business Intelligence to expand." <span>- Male, 28, Customer Success Engineer</span>
          </p>
        </div>
      </div>
    </li>
    <li>
      <div class="row">
        <div class="col-md-12">
          <h2 class="quote-title">
             96% WebCorpCo users see an 18% increase in profits the first year.
          </h2>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-10 col-xs-offset-1 col-md-10 col-md-offset-1 text-center">
          <p>
            "Look. If you have data, you need WebCorpCo. Plain and simple." <span>- Female, 29, C-Level Executive</span>
          </p>
        </div>
      </div>
    </li>
    <li>
      <div class="row">
        <div class="col-md-12">
          <h2 class="quote-title">
             96% WebCorpCo users see an 18% increase in profits the first year.
          </h2>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-10 col-xs-offset-1 col-md-10 col-md-offset-1 text-center">
          <p>
            "The whole team at WebCorpCo is truly amazing. All 560,000 of them." <span>- Male, 41, IT Solutions Architect</span>
          </p>
        </div>
      </div>
    </li>
  </ul>
</div>
```

## CSS

All required CSS is in customer-quote-slider.css

## JavaScript

The customer quote slider is initiated by the following JavaScript.

```
 $(document).ready(function() {
      $('.patient-quote').flexslider();    
    });
```

## External Resources

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
<link href="customer-quote-slider.css" rel="stylesheet">
<link href="https://cdnjs.cloudflare.com/ajax/libs/flexslider/2.6.3/flexslider.min.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/flexslider/2.6.3/jquery.flexslider-min.js"></script>
```
