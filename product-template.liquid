<!-- /templates/product.liquid -->
<div itemscope itemtype="http://schema.org/Product" id="ProductSection--{{ section.id }}" data-section-id="{{ section.id }}" data-section-type="product-template" data-image-zoom-type="{{ section.settings.zoom_enable }}" data-enable-history-state="true" data-scroll-to-image="{% if section.settings.image_layout == "stacked" %}true{% else %}false{% endif %}">

    <meta itemprop="url" content="{{ shop.url }}{{ product.url }}">
    <meta itemprop="image" content="{{ product.featured_image.src | img_url: 'grande' }}">

    {% assign current_variant = product.selected_or_first_available_variant %}
    {% assign featured_image = current_variant.featured_image | default: product.featured_image %}

    <div class="grid product-single">
      <div class="grid__item large--seven-twelfths medium--seven-twelfths text-center">

        {% if section.settings.image_layout == "stacked" %}
          {% comment %}
            Default or stacked layout
          {% endcomment %}

          {% comment %}
            We need to figure out the max width we want the image to be on the page
            based on the aspect ratio of the image and based on the size of the
            image.
          {% endcomment %}
          <div class="product-single__photos">
            {% capture img_id_class %}product-single__photo-{{ featured_image.id }}{% endcapture %}
            {% capture wrapper_id %}ProductImageWrapper-{{ featured_image.id }}{% endcapture %}

            {% comment %}
              Display current variant image
            {% endcomment %}
            <div class="product-single__photo--flex-wrapper">
              <div class="product-single__photo--flex">
                {% include 'image-style' with image: featured_image, width: 575, height: 850, small_style: true, wrapper_id: wrapper_id, img_id_class: img_id_class %}
                <div id="{{ wrapper_id }}" class="product-single__photo--container">
                  <div class="product-single__photo-wrapper" style="padding-top:{{ 1 | divided_by: featured_image.aspect_ratio | times: 100}}%;">
                    {% assign img_url = featured_image | img_url: '1x1' | replace: '_1x1.', '_{width}x.' %}
                    <img class="product-single__photo lazyload {{ img_id_class }}"
                      src="{{ featured_image | img_url: '300x300' }}"
                      data-src="{{ img_url }}"
                      data-widths="[180, 360, 590, 720, 900, 1080, 1296, 1512, 1728, 2048]"
                      data-aspectratio="{{ featured_image.aspect_ratio }}"
                      data-sizes="auto"
                      {% if section.settings.zoom_enable %}data-mfp-src="{{ featured_image | img_url: '1024x1024' }}"{% endif %}
                      data-image-id="{{ featured_image.id }}"
                      alt="{{ featured_image.alt | escape }}">

                    <noscript>
                      <img class="product-single__photo"
                        src="{{ featured_image | img_url: 'master' }}"
                        {% if section.settings.zoom_enable %}data-mfp-src="{{ featured_image | img_url: '1024x1024' }}"{% endif %}
                        alt="{{ featured_image.alt | escape }}" data-image-id="{{ featured_image.id }}">
                    </noscript>
                  </div>
                </div>
              </div>
            </div>

            {% comment %}
              Display rest of product images, not repeating the featured one
            {% endcomment %}
            {% for image in product.images %}
              {% unless image contains featured_image %}

                {% comment %}
                  We need to figure out the max width we want the image to be on the page
                  based on the aspect ratio of the image and based on the size of the
                  image.
                {% endcomment %}
                {% capture img_id_class %}product-single__photo-{{ image.id }}{% endcapture %}
                {% capture wrapper_id %}ProductImageWrapper-{{ image.id }}{% endcapture %}

                <div class="product-single__photo--flex-wrapper">
                  <div class="product-single__photo--flex">
                    {% include 'image-style' with image: image, width: 575, height: 850, small_style: true, wrapper_id: wrapper_id, img_id_class: img_id_class %}
                    <div id="{{ wrapper_id }}" class="product-single__photo--container">
                      <div class="product-single__photo-wrapper" style="padding-top:{{ 1 | divided_by: image.aspect_ratio | times: 100}}%;">
                        {% assign img_url = image | img_url: '1x1' | replace: '_1x1.', '_{width}x.' %}
                        <img class="product-single__photo lazyload {{ img_id_class }}"
                          src="{{ image | img_url: '300x' }}"
                          data-src="{{ img_url }}"
                          data-widths="[180, 360, 540, 720, 900, 1080, 1296, 1512, 1728, 2048]"
                          data-aspectratio="{{ image.aspect_ratio }}"
                          data-sizes="auto"
                          {% if section.settings.zoom_enable %}data-mfp-src="{{ image.src | img_url: '1024x1024' }}"{% endif %}
                          data-image-id="{{ image.id }}"
                          alt="{{ image.alt | escape }}">

                        <noscript>
                          <img class="product-single__photo" src="{{ image.src | img_url: 'master' }}"
                            {% if section.settings.zoom_enable %}data-mfp-src="{{ image.src | img_url: '1024x1024' }}"{% endif %}
                            alt="{{ image.alt | escape }}"
                            data-image-id="{{ image.id }}">
                        </noscript>
                      </div>
                    </div>
                  </div>
                </div>
              {% endunless %}
            {% endfor %}

          </div>

        {% else %}
          {% comment %}
            Thumbnails layout
          {% endcomment %}

          <div class="product-thumbnail__photos product-single__photos">

            {% comment %}
              We need to figure out the max width we want the image to be on the page
              based on the aspect ratio of the image and based on the size of the
              image.
            {% endcomment %}
            {% capture img_id_class %}product-single__photo-{{ featured_image.id }}{% endcapture %}
            {% capture wrapper_id %}ProductImageWrapper-{{ featured_image.id }}{% endcapture %}

            {% comment %}
              Display current variant image
            {% endcomment %}
            <div class="product-single__photo--flex-wrapper">
              <div class="product-single__photo--flex">
                {% include 'image-style' with image: featured_image, width: 575, height: 850, small_style: true, wrapper_id: wrapper_id, img_id_class: img_id_class %}
                <div id="{{ wrapper_id }}" class="product-single__photo--container product-single__photo--container-thumb">
                  <div class="product-single__photo-wrapper" style="padding-top:{{ 1 | divided_by: featured_image.aspect_ratio | times: 100}}%;">
                    {% assign img_url = featured_image | img_url: '1x1' | replace: '_1x1.', '_{width}x.' %}
                    <img class="product-single__photo lazyload {{ img_id_class }}"
                      src="{{ featured_image | img_url: '300x300' }}"
                      data-src="{{ img_url }}"
                      data-widths="[180, 360, 590, 720, 900, 1080, 1296, 1512, 1728, 2048]"
                      data-aspectratio="{{ featured_image.aspect_ratio }}"
                      data-sizes="auto"
                      {% if section.settings.zoom_enable %}data-mfp-src="{{ featured_image | img_url: '1024x1024' }}"{% endif %}
                      data-image-id="{{ featured_image.id }}"
                      alt="{{ featured_image.alt | escape }}">

                    <noscript>
                      <img class="product-single__photo"
                        src="{{ featured_image | img_url: 'master' }}"
                        {% if section.settings.zoom_enable %}data-mfp-src="{{ featured_image | img_url: '1024x1024' }}"{% endif %}
                        alt="{{ featured_image.alt | escape }}" data-image-id="{{ featured_image.id }}">
                    </noscript>
                  </div>
                </div>
              </div>
            </div>

            {% comment %}
              Populate rest of product images with display = none, not repeating the featured one
            {% endcomment %}
            {% for image in product.images %}
              {% unless image contains featured_image %}

                {% comment %}
                  We need to figure out the max width we want the image to be on the page
                  based on the aspect ratio of the image and based on the size of the
                  image.
                {% endcomment %}
                {% capture img_id_class %}product-single__photo-{{ image.id }}{% endcapture %}
                {% capture wrapper_id %}ProductImageWrapper-{{ image.id }}{% endcapture %}

                <div class="product-single__photo--flex-wrapper">
                  <div class="product-single__photo--flex">
                    {% include 'image-style' with image: image, width: 575, height: 850, small_style: true, wrapper_id: wrapper_id, img_id_class: img_id_class %}
                    <div id="{{ wrapper_id }}" class="product-single__photo--container product-single__photo--container-thumb hide">
                      <div class="product-single__photo-wrapper" style="padding-top:{{ 1 | divided_by: image.aspect_ratio | times: 100}}%;">
                        {% assign img_url = image | img_url: '1x1' | replace: '_1x1.', '_{width}x.' %}
                        <img class="product-single__photo lazyload {{ img_id_class }}"
                          src="{{ image | img_url: '300x' }}"
                          data-src="{{ img_url }}"
                          data-widths="[180, 360, 540, 720, 900, 1080, 1296, 1512, 1728, 2048]"
                          data-aspectratio="{{ image.aspect_ratio }}"
                          data-sizes="auto"
                          {% if section.settings.zoom_enable %}data-mfp-src="{{ image.src | img_url: '1024x1024' }}"{% endif %}
                          data-image-id="{{ image.id }}"
                          alt="{{ image.alt | escape }}">

                        <noscript>
                          <img class="product-single__photo" src="{{ image.src | img_url: 'master' }}"
                            {% if section.settings.zoom_enable %}data-mfp-src="{{ image.src | img_url: '1024x1024' }}"{% endif %}
                            alt="{{ image.alt | escape }}"
                            data-image-id="{{ image.id }}">
                        </noscript>
                      </div>
                    </div>
                  </div>
                </div>
              {% endunless %}
            {% endfor %}

            {% comment %}
              Display thumbnails
            {% endcomment %}
            <ul class="product-single__thumbnails small--hide grid-uniform" id="ProductThumbs">
              {% for image in product.images %}
                {% if product.images.size > 1 %}
                  <li class="grid__item medium--one-third large--one-quarter product-single__photo-wrapper">
                    <a data-image-id="{{ image.id }}" href="{{ image.src | img_url: 'grande' }}" class="product-single__thumbnail {% if image contains featured_image %} active-thumb{% endif %}">
                      <img class="product-single__thumb" src="{{ image.src | img_url: '150x' }}" alt="{{ image.alt | escape }}">
                    </a>
                  </li>
                {% endif %}
              {% endfor %}
            </ul>

          </div>
        {% endif %}
      </div>

      <div class="grid__item product-single__meta--wrapper medium--five-twelfths large--five-twelfths">
        <div class="product-single__meta">
          {% if section.settings.product_vendor_enable %}
            <h2 class="product-single__vendor" itemprop="brand">{{ product.vendor }}</h2>
          {% endif %}

          <h1 class="product-single__title" itemprop="name">{{ product.title }}</h1>
{% comment %}Start automatically added Judge.me widget{% endcomment %}
  {% include 'judgeme_widgets', widget_type: 'judgeme_preview_badge', concierge_install: true %}
{% comment %}End automatically added Judge.me widget{% endcomment %}


          <div itemprop="offers" itemscope itemtype="http://schema.org/Offer">
            {% comment %}
              Optionally show the 'compare at' or original price of the product.
            {% endcomment %}
            {% include 'product-price', variant: current_variant %}

            {%- if shop.taxes_included or shop.shipping_policy.body != blank -%}
              <div class="product-single__policies rte">
                {%- if shop.taxes_included -%}
                  {{ 'products.general.include_taxes' | t }}
                {%- endif -%}
                {%- if shop.shipping_policy.body != blank -%}
                  {{ 'products.general.shipping_policy_html' | t: link: shop.shipping_policy.url }}
                {%- endif -%}
              </div>
            {%- endif -%}

            <hr class="hr--small">

</form>
      <style>#progress_bar{margin-top:15px}.progressbar.progressbar{background:#ffe8e8;border:0px solid whitesmoke;height:11px}.progressbar.progressbar div{background:#d95350;height:11px}.progressbar.progressbar.active div{-webkit-animation:2s linear 0s normal none infinite running progress-bar-stripes;animation:2s linear 0s normal none infinite running progress-bar-stripes}.progress-striped.progressbar.progressbar div{background-image:-webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);background-image:linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, rgba(0, 0, 0, 0) 25%, rgba(0, 0, 0, 0) 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, rgba(0, 0, 0, 0) 75%, rgba(0, 0, 0, 0));background-size:40px 40px}.items-count{margin-top:0px;margin-bottom:0px}.count{color:#a94442;padding:1px}.items-count p{padding-bottom:5px;margin:0;text-transform:uppercase;font-weight:700;text-align:center;font-family:"Open Sans",Arial,sans-serif}.progressbar{position:relative;display:block;background-color:#ca0000;border:1px solid #ddd;margin-bottom:15px;-webkit-box-shadow:inset 0 1px 2px rgba(0, 0, 0, .1);box-shadow:inset 0 1px 2px rgba(0, 0, 0, .1)}.progressbar > div{background-color:#ca0000;width:0;margin-bottom:0;height:15px}.progressbar > div.less-than-ten{background-color:#ca0000 !important}#clock-ticker{display:block;margin-bottom:15px}#clock-ticker .block{position:relative;color:#000;font-weight:bold;float:left;text-align:center;width:25%}#clock-ticker .block .flip-top{width:88px;height:39px;line-height:40px;font-size:40px;text-align:center}#clock-ticker .block .label,span.flip-top{color:#000;font-weight:bold;text-align:center;font-size:14px;text-transform:uppercase;width:88px;line-height:25px;font-family:"Open Sans",Arial,sans-serif}</style>
 
<script type="text/javascript">
function randomIntFromInterval(min, max) {return Math.floor(Math.random() * (max - min + 1) + min);}
 
// Settings are here
var total_items = 50;
var d = new Date();
var min_items_left = 12;
var max_items_left = 20;
var remaining_items = randomIntFromInterval(min_items_left, max_items_left);
var min_of_remaining_items = 1;
var decrease_after = 1.7; 
var decrease_after_first_item = 0.17; 
 
// Davy Jones' Locker
(function($){$.fn.progressbar=function(){var a="<p>SALE ENDING IN...</p>"+"<div class='progressbar'><div style='width:100%'></div></div>";this.addClass('items-count');this.html(a+this.html());updateMeter(this);var b=this;setTimeout(function(){remaining_items--;if(remaining_items<min_of_remaining_items){remaining_items=randomIntFromInterval(min_items_left,max_items_left)}$('.count').css('background-color','#CE0201');$('.count').css('color','#fff');setTimeout(function(){$('.count').css('background-color','#fff');$('.count').css('color','#CE0201')},1000*60*0.03);b.find(".count").text(remaining_items);updateMeter(b)},1000*60*decrease_after_first_item);setInterval(function(){remaining_items--;if(remaining_items<min_of_remaining_items){remaining_items=randomIntFromInterval(min_items_left,max_items_left)}$('.count').css('background-color','#CE0201');$('.count').css('color','#fff');setTimeout(function(){$('.count').css('background-color','#fff');$('.count').css('color','#CE0201')},1000*60*0.03);b.find(".count").text(remaining_items);updateMeter(b)},1000*60*decrease_after)};function updateMeter(a){var b=100*remaining_items/total_items;if(remaining_items<10){a.find('.progressbar div:first').addClass('less-than-ten')}a.find('.progressbar').addClass('active progress-striped');setTimeout(function(){myanimate(a.find('.progressbar div:first'),b);a.find('.progressbar').removeClass('active progress-striped')},1000)}}(jQuery));function myanimate(a,b){var c=0;var d=parseInt(a.closest('.progressbar').css('width'));var e=Math.floor(100*parseInt(a.css('width'))/d);if(e>b){c=e}function frame(){if(e>b){c--}else{c++}a.css('width',c+'%');if(c==b||c<=0||c>=100)clearInterval(f)}var f=setInterval(frame,40)} $(document).ready(function(){$("#progress_bar").progressbar();var tag="ctdn-12-12".match(/\d+/g);var hour=14;var theDaysBox=$("#numdays");var theHoursBox=$("#numhours");var theMinsBox=$("#nummins");var theSecsBox=$("#numsecs");var d=new Date();var n=d.getDay();var date=1;var gg=0;var hh=0;var ii=0;var nsec=0-d.getSeconds();if(nsec<0){nsec=60-d.getSeconds();gg=1}var nmin=0-d.getMinutes()-gg;if(nmin<0){nmin=60-d.getMinutes()-gg;hh=1}var nhrs=14-d.getHours()-hh;if(nhrs<0){nhrs=38-d.getHours()-hh;ii=1}var ndat=date-1;if(ndat<0){var mmon=d.getMonth();ndat=30+date-d.getDate()-ii}theSecsBox.html(nsec);theMinsBox.html(nmin);theHoursBox.html(nhrs);theDaysBox.html(ndat);var refreshId=setInterval(function(){var e=theSecsBox.text();var a=theMinsBox.text();var c=theHoursBox.text();var b=theDaysBox.text();if(e==0&&a==0&&c==0&&b==0){}else{if(e==0&&a==0&&c==0){theDaysBox.html(b-1);theHoursBox.html("23");theMinsBox.html("59");theSecsBox.html("59")}else{if(e==0&&a==0){theHoursBox.html(c-1);theMinsBox.html("59");theSecsBox.html("59")}else{if(e==0){theMinsBox.html(a-1);theSecsBox.html("59")}else{theSecsBox.html(e-1)}}}}},1000);});</script>
<div class="items-count" id="progress_bar"></div><div id="clock-ticker" class="clearfix"><div class="block"><span class="flip-top" id="numdays">0</span><br><span class="label">Days</span></div><div class="block"><span class="flip-top" id="numhours">1</span><br><span class="label">Hours</span></div><div class="block"><span class="flip-top" id="nummins">23</span><br><span class="label">Minutes</span></div><div class="block"><span class="flip-top" id="numsecs">36</span><br><span class="label">Seconds</span></div>
</div>

            <meta itemprop="priceCurrency" content="{{ cart.currency.iso_code }}">
            <link itemprop="availability" href="http://schema.org/{% if product.available %}InStock{% else %}OutOfStock{% endif %}">

            {% capture "form_classes" %}
              product-single__form{% if product.has_only_default_variant %} product-single__form--no-variants{% endif %}
            {%- endcapture %}

            {% capture "form_id" %}AddToCartForm--{{ section.id }}{%- endcapture %}

            {% form 'product', product, class:form_classes, id:form_id, data-product-form: '' %}
              {% unless product.has_only_default_variant %}
                {% for option in product.options_with_values %}
                  <div class="radio-wrapper js product-form__item">
                    <label class="single-option-radio__label"
                      for="ProductSelect-option-{{ forloop.index0 }}">
                      {{ option.name | escape }}
                    </label>
                    {% if section.settings.product_selector == 'radio' %}
                      <fieldset class="single-option-radio"
                        id="ProductSelect-option-{{ forloop.index0 }}">
                        {% assign option_index = forloop.index %}
                        {% for value in option.values %}
                          {% assign variant_label_state = true %}
                          {% if product.options.size == 1 %}
                            {% unless product.variants[forloop.index0].available  %}
                              {% assign variant_label_state = false %}
                            {% endunless %}
                          {% endif %}
                          <input type="radio"
                            {% if option.selected_value == value %} checked="checked"{% endif %}
                            {% unless variant_label_state %} disabled="disabled"{% endunless %}
                            value="{{ value | escape }}"
                            data-index="option{{ option_index }}"
                            name="option{{ option.position }}"
                            class="single-option-selector__radio{% unless variant_label_state %} disabled{% endunless %}"
                            id="ProductSelect-option-{{ option.name | handleize }}-{{ value | escape }}">
                          <label for="ProductSelect-option-{{ option.name | handleize }}-{{ value | escape }}"{% unless variant_label_state %} class="disabled"{% endunless %}>{{ value | escape }}</label>
                        {% endfor %}
                      </fieldset>
                    {% else %}
                      <select class="single-option-selector__radio single-option-selector-{{ section.id }} product-form__input" id="SingleOptionSelector-{{ forloop.index0 }}" data-index="option{{ forloop.index }}">
                        {% for value in option.values %}
                          <option value="{{ value | escape }}"{% if option.selected_value == value %} selected="selected"{% endif %}>{{ value | escape }}</option>
                        {% endfor %}
                      </select>
                    {% endif %}
                  </div>
                {% endfor %}
              {% endunless %}

              <select name="id" id="ProductSelect" class="product-single__variants no-js">
                {% for variant in product.variants %}
                  {% if variant.available %}
                    <option {% if variant == product.selected_or_first_available_variant %}
                      selected="selected" {% endif %}
                      data-sku="{{ variant.sku }}"
                      value="{{ variant.id }}">
                      {{ variant.title }} - {{ variant.price | money_with_currency }}
                    </option>
                  {% else %}
                    <option disabled="disabled">
                      {{ variant.title }} - {{ 'products.product.sold_out' | t }}
                    </option>
                  {% endif %}
                {% endfor %}
              </select>


              {% if section.settings.quantity_enabled %}
              <div class="product-single__quantity">
                <label for="Quantity" class="product-single__quantity-label js-quantity-selector">{{ 'products.product.quantity' | t }}</label>
                <input type="number" hidden="hidden" id="Quantity" name="quantity" value="1" min="1" class="js-quantity-selector">
              </div>
              {% endif %}



              <div class="product-single__add-to-cart{% if section.settings.add_to_cart_button_size == 'large' %} product-single__add-to-cart--full-width{% endif %}">
                <button type="submit" name="add" id="AddToCart--{{ section.id }}" class="btn btn--add-to-cart{% if section.settings.enable_payment_button %} btn--secondary-accent{% endif %}"{% unless current_variant.available %}
disabled="disabled"{% endunless %}
style="background-color: #ff0000; width: 100%; height: 94px; font-weight: Regular; font-size: 30px; color: white;">
                  <span class="btn__text">
                    {% if current_variant.available %}
                      {{ 'products.product.add_to_cart' | t }}
                    {% else %}
                      {{ 'products.product.sold_out' | t }}
                    {% endif %}
                  </span>
                </button>
                {% if section.settings.enable_payment_button %}
                  {{ form | payment_button }}
                {% endif %}
              </div>
           {% endform %}

          </div>
<img src=https://cdn.shopify.com/s/files/1/0266/3851/6258/files/pngkey.com-trust-badge-png-3598708.png>
          <div class="product-single__description rte" itemprop="description">
            {{ product.description }}
          </div>
          {% if section.settings.social_sharing_products %}
            {% include 'social-sharing', share_title: product.title, share_permalink: product.url, share_image: product %}
          {% endif %}
        </div>
      </div>
    </div>
{% comment %}Start automatically added Judge.me widget{% endcomment %}
  {% include 'judgeme_widgets', widget_type: 'judgeme_review_widget', concierge_install: true %}
{% comment %}End automatically added Judge.me widget{% endcomment %}

</div>
{% unless product == empty %}
  <script type="application/json" id="ProductJson-{{ section.id }}">
    {{ product | json }}
  </script>
{% endunless %}



{% schema %}
{
  "name": {
    "da": "Produktsider",
    "de": "Produktseiten",
    "en": "Product pages",
    "es": "Páginas de productos",
    "fi": "Tuotesivut",
    "fr": "Pages de produits",
    "hi": "उत्पाद पेज",
    "it": "Pagine di prodotto",
    "ja": "商品ページ",
    "ko": "제품 페이지",
    "ms": "Halaman produk",
    "nb": "Produktsider",
    "nl": "Productpagina's",
    "pt-BR": "Páginas de produtos",
    "pt-PT": "Páginas de produtos",
    "sv": "Produktsidor",
    "th": "หน้าสินค้า",
    "zh-CN": "产品页面",
    "zh-TW": "產品頁面"
  },
  "settings": [
    {
      "type": "checkbox",
      "id": "zoom_enable",
      "label": {
        "da": "Aktivér billedzoom",
        "de": "Aktivieren des Bildzooms",
        "en": "Enable image zoom",
        "es": "Habilitar zoom de imagen",
        "fi": "Ota kuvan zoomaus käyttöön",
        "fr": "Activer le zoom sur image",
        "hi": "इमेज ज़ूम सक्षम करें",
        "it": "Abilita lo zoom dell'immagine",
        "ja": "画像ズームを有効にする",
        "ko": "이미지 확대 사용",
        "ms": "Dayakan zum imej",
        "nb": "Aktiver bildezoom",
        "nl": "Inzoomen op afbeelding inschakelen",
        "pt-BR": "Ative o zoom da imagem",
        "pt-PT": "Ativar o zoom da imagem",
        "sv": "Aktivera bildzoom",
        "th": "เปิดใช้การซูมภาพ",
        "zh-CN": "启用图片缩放",
        "zh-TW": "啟用圖片縮放"
      }
    },
    {
      "type": "checkbox",
      "id": "social_sharing_products",
      "label": {
        "da": "Aktivér produktdeling",
        "de": "Teilen von Produkten aktivieren",
        "en": "Enable product sharing",
        "es": "Habilitar compartir productos",
        "fi": "Ota tuotejako käyttöön",
        "fr": "Activer le partage de produits",
        "hi": "उत्पाद साझाकरण सक्षम करें",
        "it": "Permetti condivisione del prodotto",
        "ja": "商品の共有を有効にする",
        "ko": "제품 공유 활성화",
        "ms": "Dayakan perkongsian produk",
        "nb": "Aktiver produktdeling",
        "nl": "Schakel het delen van producten in",
        "pt-BR": "Habilite o compartilhamento de produtos",
        "pt-PT": "Ativar a partilha de produtos",
        "sv": "Aktivera produktdelning",
        "th": "เปิดใช้การแชร์สินค้า",
        "zh-CN": "启用产品分享",
        "zh-TW": "啟用產品分享"
      },
      "default": true
    },
    {
      "type": "checkbox",
      "id": "product_vendor_enable",
      "label": {
        "da": "Vis produktleverandør",
        "de": "Produktverkäufer anzeigen",
        "en": "Show product vendor",
        "es": "Mostrar proveedor del producto",
        "fi": "Näytä tuotteen myyjä",
        "fr": "Afficher le distributeur du produit",
        "hi": "उत्पाद विक्रेता दिखाएं",
        "it": "Indica fornitore prodotto",
        "ja": "商品の販売元を表示する",
        "ko": "제품 공급 업체 표시",
        "ms": "Tunjukkan vendor produk",
        "nb": "Vis produktleverandør",
        "nl": "Productleverancier weergeven",
        "pt-BR": "Exiba o fornecedor do produto",
        "pt-PT": "Mostrar o fornecedor do produto",
        "sv": "Visa produktsäljare",
        "th": "แสดงผู้ขายสินค้า",
        "zh-CN": "显示产品厂商",
        "zh-TW": "顯示產品廠商"
      }
    },
    {
      "type": "select",
      "id": "image_layout",
      "label": {
        "da": "Billedvisning",
        "de": "Bildanzeige",
        "en": "Image display",
        "es": "Visualización de imagen",
        "fi": "Näytä kuva",
        "fr": "Affichage de l'image",
        "hi": "इमेज प्रदर्शन",
        "it": "Visualizzazione immagine",
        "ja": "画像表示",
        "ko": "이미지 표시",
        "ms": "Paparan imej",
        "nb": "Bildevisning",
        "nl": "Beeldweergave",
        "pt-BR": "Exibição de imagem",
        "pt-PT": "Apresentação de imagem",
        "sv": "Bildskärm",
        "th": "การแสดงรูปภาพ",
        "zh-CN": "图片显示",
        "zh-TW": "圖片顯示"
      },
      "default": "stacked",
      "options": [
        {
          "value": "stacked",
          "label": {
            "da": "Stablet",
            "de": "Gestapelt",
            "en": "Stacked",
            "es": "Stacked",
            "fi": "Pinottu",
            "fr": "Empiler",
            "hi": "स्टैक्ड",
            "it": "Elenco",
            "ja": "スタックされました",
            "ko": "누적",
            "ms": "Ditindan",
            "nb": "Stablet",
            "nl": "Gestapeld",
            "pt-BR": "Empilhado",
            "pt-PT": "Empilhado",
            "sv": "Staplade",
            "th": "ซ้อน",
            "zh-CN": "已堆叠",
            "zh-TW": "已堆疊"
          }
        },
        {
          "value": "thumbnails",
          "label": {
            "da": "Miniaturer",
            "de": "Vorschaubilder",
            "en": "Thumbnails",
            "es": "Miniaturas",
            "fi": "Pikkukuvat",
            "fr": "Vignettes",
            "hi": "थंबनेल",
            "it": "Miniature",
            "ja": "サムネイル",
            "ko": "썸네일",
            "ms": "Imej kecil",
            "nb": "Miniatyrbilder",
            "nl": "Miniatuurafbeeldingen",
            "pt-BR": "Miniaturas",
            "pt-PT": "Miniaturas",
            "sv": "Förhandsbilder",
            "th": "ขนาดย่อ",
            "zh-CN": "缩略图",
            "zh-TW": "縮圖"
          }
        }
      ]
    },
    {
      "type": "header",
      "content": {
        "da": "Formular for produktmuligheder",
        "de": "Produktoptionsformular",
        "en": "Product options form",
        "es": "Formulario de opciones de producto",
        "fi": "Tuotevaihtoehtolomake",
        "fr": "Formulaire d'options de produit",
        "hi": "उत्पाद के विकल्प फ़ॉर्म",
        "it": "Modulo delle opzioni di prodotto",
        "ja": "商品オプションのフォーム",
        "ko": "제품 옵션 양식",
        "ms": "Borang opsyen produk",
        "nb": "Skjema for produktalternativer",
        "nl": "Formulier productopties",
        "pt-BR": "Formulário de opções de produtos",
        "pt-PT": "Formulário de opções de produtos",
        "sv": "Produktalternativsformulär",
        "th": "แบบฟอร์มตัวเลือกสินค้า",
        "zh-CN": "产品选项表单",
        "zh-TW": "產品選項表單"
      }
    },
    {
      "type": "checkbox",
      "id": "quantity_enabled",
      "label": {
        "da": "Vis antalsvælger",
        "de": "Mengenauswahl anzeigen",
        "en": "Show quantity picker",
        "es": "Mostrar selector de cantidad",
        "fi": "Näytä määrän valintatyökalu",
        "fr": "Afficher le sélecteur de quantité",
        "hi": "मात्रा पिकर दिखाएं",
        "it": "Mostra selettore di quantità",
        "ja": "数量ピッカーを表示する",
        "ko": "수량 피커 표시",
        "ms": "Tunjukkan pemetik kuantiti",
        "nb": "Vis mengdevelger",
        "nl": "Hoeveelheidskiezer weergeven",
        "pt-BR": "Exibir seletor de quantidade",
        "pt-PT": "Mostrar seletor de quantidade",
        "sv": "Visa kvantitetsväljaren",
        "th": "แสดงตัวเลือกจำนวน",
        "zh-CN": "显示数量选择器",
        "zh-TW": "顯示數量選擇器"
      }
    },
    {
      "type": "select",
      "id": "product_selector",
      "label": {
        "da": "Vælgertype",
        "de": "Auswahlart",
        "en": "Picker type",
        "es": "Tipo de selector",
        "fi": "Määrän valintatyökalu",
        "fr": "Type de sélecteur",
        "hi": "पिकर के प्रकार",
        "it": "Tipo di selettore",
        "ja": "ピッカーの種類",
        "ko": "피커 유형",
        "ms": "Jenis pemetik",
        "nb": "Velgertype",
        "nl": "Soort kiezer",
        "pt-BR": "Tipo de seletor",
        "pt-PT": "Tipo de seletor",
        "sv": "Väljartyp",
        "th": "ประเภทของตัวเลือก",
        "zh-CN": "选择器类型",
        "zh-TW": "選擇器類型"
      },
      "options": [
        {
          "value": "radio",
          "label": {
            "da": "Knap",
            "de": "Schaltfläche",
            "en": "Button",
            "es": "Botón",
            "fi": "Painike",
            "fr": "Bouton",
            "hi": "बटन",
            "it": "Pulsante",
            "ja": "ボタン",
            "ko": "버튼",
            "ms": "Butang",
            "nb": "Knapp",
            "nl": "Knop",
            "pt-BR": "Botão",
            "pt-PT": "Botão",
            "sv": "Knapp",
            "th": "ปุ่ม",
            "zh-CN": "按钮",
            "zh-TW": "按鈕"
          }
        },
        {
          "value": "select",
          "label": {
            "da": "Rullemenu",
            "de": "Dropdown",
            "en": "Dropdown",
            "es": "Desplegable",
            "fi": "Alasvetovalikko",
            "fr": "Menu déroulant",
            "hi": "ड्रॉप डाउन",
            "it": "Menu a tendina",
            "ja": "ドロップダウン",
            "ko": "드롭다운",
            "ms": "Juntai bawah",
            "nb": "Rullegardin",
            "nl": "Vervolgkeuzemenu",
            "pt-BR": "Menu suspenso",
            "pt-PT": "Menu pendente",
            "sv": "Rullgardinsmeny",
            "th": "ดรอปดาวน์",
            "zh-CN": "下拉菜单",
            "zh-TW": "下拉式選單"
          }
        }
      ]
    },
    {
      "type": "header",
      "content": {
        "da": "Knappen Læg i indkøbskurven",
        "de": "Schaltfläche In den Warenkorb",
        "en": "Add to cart button",
        "es": "Añadir al carrito",
        "fi": "Lisää ostoskoriin -painike",
        "fr": "Bouton d'ajout au panier",
        "hi": "कार्ट बटन में जोड़ें",
        "it": "Pulsante \"Aggiungi al carrello\"",
        "ja": "カートボタンに追加する",
        "ko": "카트 버튼에 추가",
        "ms": "Tambahkan ke butang troli",
        "nb": "Legg i handlekurv-knapp",
        "nl": "Knop aan winkelwagen toevoegen",
        "pt-BR": "Botão Adicionar ao carrinho",
        "pt-PT": "Botão Adicionar ao carrinho",
        "sv": "Lägg i varukorgen-knappen",
        "th": "ปุ่มเพิ่มลงในตะกร้าสินค้า",
        "zh-CN": "“添加到购物车”按钮",
        "zh-TW": "加入購物車按鈕"
      }
    },
    {
      "type": "checkbox",
      "id": "enable_payment_button",
      "label": {
        "da": "Vis dynamisk betalingsknap",
        "de": "Dynamischen Checkout-Button anzeigen",
        "en": "Show dynamic checkout button",
        "es": "Mostrar botón de pago dinámico",
        "fi": "Näytä dynaaminen kassapainike",
        "fr": "Afficher le bouton de passage à la caisse dynamique",
        "hi": "डायनेमिक चेकआउट बटन दिखाएं",
        "it": "Mostra pulsante di check-out dinamico",
        "ja": "ダイナミックチェックアウトボタンを表示する",
        "ko": "동적 결제 버튼 표시",
        "ms": "Tunjukkan butang daftar keluar dinamik",
        "nb": "Vis dynamisk knapp for å gå til kassen",
        "nl": "Dynamische checkout knop weergeven",
        "pt-BR": "Exibir botão dinâmico de finalização da compra",
        "pt-PT": "Mostrar o botão dinâmico de finalização da compra",
        "sv": "Visa dynamiska utcheckningsknappar",
        "th": "แสดงปุ่มชำระเงินแบบไดนามิก",
        "zh-CN": "显示动态结账按钮",
        "zh-TW": "顯示動態結帳按鈕"
      },
      "info": {
        "da": "Den enkelte kunde vil se sin foretrukne betalingsmetode blandt dem, der er tilgængelige i din butik, f.eks. PayPal eller Apple Pay. [Få mere at vide](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "de": "Jeder Kunde sieht seine bevorzugte Zahlungsmethode aus den in Ihrem Shop verfügbaren Zahlungsmethoden wie PayPal oder Apple Pay. [Mehr Informationen](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "en": "Each customer will see their preferred payment method from those available on your store, such as PayPal or Apple Pay. [Learn more](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "es": "Cada cliente verá su forma de pago preferida entre las disponibles en tu tienda, como PayPal o Apple Pay. [Más información](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "fi": "Kukin asiakas näkee ensisijaisen valintansa kauppasi tarjoamista maksutavoista, esim. PayPal tai Apple Pay. [Lisätietoja](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "fr": "Chaque client verra son moyen de paiement préféré parmi ceux qui sont proposés sur votre boutique, tels que PayPal ou Apple Pay. [En savoir plus](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "hi": "प्रत्येक ग्राहक आपके स्टोर पर उपलब्ध अपनी पसंदीदा भुगतान की विधि देखेंगे जैसे PayPal या Apple Pay. [अधिक जानें](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "it": "Ogni cliente vedrà il suo metodo di pagamento preferito tra quelli disponibili nel tuo negozio, come PayPal o Apple Pay. [Maggiori informazioni](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "ja": "PayPalやApple Payなど、ストアで利用可能な希望の決済方法がお客様に表示されます。[詳細情報](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "ko": "각 고객은 PayPal 또는 Apple Pay와 같이 스토어에서 사용 가능한 지불 방법을 확인할 수 있습니다. [자세히 알아보기](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "ms": "Setiap pelanggan akan melihat kaedah pembayaran keutamaan mereka dari yang tersedia di kedai anda, seperti PayPal atau Apple Pay. [Ketahui lebih lanjut](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "nb": "Hver enkelt kunde vil se sin foretrukne betalingsmåte blant de som er tilgjengelig i butikken din, som PayPal eller Apple Pay. [Finn ut mer](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "nl": "Elke klant ziet zijn of haar beschikbare voorkeursmethode om af te rekenen, zoals PayPal of Apple Pay. [Meer informatie](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "pt-BR": "Cada cliente verá seu método de pagamento preferido dentre os disponíveis na loja, como PayPal ou Apple Pay. [Saiba mais](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "pt-PT": "Cada cliente irá ver o seu método de pagamento preferido entre os disponíveis na loja, como o PayPal ou Apple Pay. [Saiba mais](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "sv": "Varje kund kommer att se den föredragna betalningsmetoden från de som finns tillgängliga i din butik, till exempel PayPal eller Apple Pay. [Läs mer](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "th": "ลูกค้าแต่ละรายจะเห็นวิธีการชำระเงินที่ต้องการจากวิธีที่ใช้ได้ในร้านค้าของคุณ เช่น PayPal หรือ Apple Pay [เรียนรู้เพิ่มเติม](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "zh-CN": "每位客户都可在您商店提供的付款方式中看到他们的首选付款方式，例如 PayPal 或 Apple Pay。[了解详情](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)",
        "zh-TW": "每位客戶都可以在您商店內開放使用的付款方式中看見他們偏好使用的方式，如 PayPal、Apple Pay 等。[深入瞭解](https://help.shopify.com/manual/using-themes/change-the-layout/dynamic-checkout)"
      },
      "default": true
    },
    {
      "type": "select",
      "id": "add_to_cart_button_size",
      "label": {
        "da": "Knapstørrelse",
        "de": "Schaltflächengröße",
        "en": "Button size",
        "es": "Tamaño del botón",
        "fi": "Painikkeen koko",
        "fr": "Taille du bouton",
        "hi": "बटन का आकार",
        "it": "Dimensione pulsante",
        "ja": "ボタンのサイズ",
        "ko": "버튼 사이즈",
        "ms": "Saiz butang",
        "nb": "Knappestørrelse",
        "nl": "Afmeting knop",
        "pt-BR": "Tamanho do botão",
        "pt-PT": "Tamanho do botão",
        "sv": "Knappstorlek",
        "th": "ขนาดปุ่ม",
        "zh-CN": "按钮大小",
        "zh-TW": "按鈕尺寸"
      },
      "default": "small",
      "options": [
        {
          "value": "small",
          "label": {
            "da": "Lille",
            "de": "Klein",
            "en": "Small",
            "es": "Pequeña",
            "fi": "Pieni",
            "fr": "Petit",
            "hi": "छोटा",
            "it": "Piccolo",
            "ja": "小",
            "ko": "스몰",
            "ms": "Kecil",
            "nb": "Liten",
            "nl": "Klein",
            "pt-BR": "Pequeno",
            "pt-PT": "Pequeno",
            "sv": "Liten",
            "th": "เล็ก",
            "zh-CN": "小",
            "zh-TW": "小型"
          }
        },
        {
          "value": "large",
          "label": {
            "da": "Stor",
            "de": "Groß",
            "en": "Large",
            "es": "grande",
            "fi": "Suuri",
            "fr": "Grand",
            "hi": "बड़ा",
            "it": "Grande",
            "ja": "大",
            "ko": "라지",
            "ms": "Besar",
            "nb": "Stor",
            "nl": "Groot",
            "pt-BR": "Grande",
            "pt-PT": "Grande",
            "sv": "Stor",
            "th": "ใหญ่",
            "zh-CN": "大",
            "zh-TW": "大型"
          }
        }
      ]
    }
  ]
}
{% endschema %}
  {%include 'customanimator' %}
