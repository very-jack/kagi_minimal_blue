# kagi_minimal_blue
Based on the color scheme of [my personal blog](https://veryjack.com), I customized the CSS for Kagi.

Custom CSS Steps:
In Kagi, click on the Settings icon in the top-right corner, go to Appearance, then select Custom CSS. Copy [the content](./kagi_minimal_blue.css) below into the text box and save it.

```
:root {
    --result-item-title-border: var(--highlight-color);
    --border-color: #f3f4f7;
    --highlight-color: #98c1d9;
  }

.theme_light {
    --title-color: #293241;
    --text-color: #475671;
    --after-color: #A9AAAE;   
    --other-color: #ffffff;
    --primary:#475671;
    --primary-hover:#98c1d9;
    --search-result-content-text:#475671;
     }
  
  .theme_dark, .theme_moon_dark {
    --title-color: #ffffff;
    --text-color: #ffffff;
    --after-color: #475671;
    --other-color: #475671;
    --search-result-content-text: #ffffff;
    --image_brightness: 85%; }
  
  
  
  a.__sri_title_link._ext_t._0_sri_title_link._0_URL {
    font-weight: 700;
    font-style: normal;
    color: var(--title-color);
    border-bottom: none;
  }
  
  a.__sri_title_link._ext_t._0_sri_title_link._0_URL:hover {
    color: var(--highlight-color);  /* 鼠标悬停时的颜色 */
    border-bottom: none;
  }
  
  a.__sri_title_link._ext_t._0_sri_title_link._0_URL:visited {
    color: var(--after-color);  /* 点击后的颜色 */
  }
  
  a.__sri_title_link._ext_t._0_sri_title_link._0_URL:visited:hover {
    color: var(--highlight-color);  /* 点击后的颜色 */
  }

  a._0_URL {
    color: var(--title-color);
    border-bottom: 0px solid var(--highlight-color);
  }
  
  div.__sri_url_path_box {
    color: var(--text-color);
  }
  
  div div div {
    color: var(--text-color);
  }
  
  div div svg {
    color: var(--title-color);
  }
  
  a._0_URL:hover  {
    color: var(--highlight-color);
    border-bottom: 0px solid var(--highlight-color);
  }
  
  a._0_URL:visited {
    color: var(--after-color);
  }
  
  a._0_URL:visited:hover {
    color: var(--highlight-color);
  }
  
  a.nav_item._0_query_link_item {
    color: var(--title-color);
    font-weight: 700;
  }
  
  a.inlineHeader:hover {
    color: var(--highlight-color);
  }
  
  a.btn.--secondary.--block{
    color: var(--text-color);
    border-color: var(--text-color);
    font-weight: 700;
  }
  
  a.btn.--secondary.--block:hover {
    color: var(--highlight-color);
    border-color: var(--highlight-color);
    font-weight: 700;
  }
  
  span.smw-less:hover {
    color: var(--highlight-color);
  }
  label.smw:hover {
    color: var(--highlight-color);
  }
  span.smw-more:hover {
    color: var(--highlight-color);
  }
  
  div._0_results_summary_box.__0_show {
    border: 2px solid var(--border-color);  /* 边框颜色 */
    border-radius: 14px;        /* 圆角效果 */
    padding: 20px;              /* 增加内边距 */
  }
  
  
  .doggo_sit_a {
    display: none;
  }
  
  div div b {
    font-size: 24px;
    font-weight: 700;
    font-style: normal;
    color: var(--title-color);
  }
  
  a.share_url_footer_content.copyToClipLink:hover {
    color: var(--highlight-color);
  }
  
  
  /* Style buttons */
  .btn.--primary {
    background-color: var(--title-color);
    border: 1px solid var(--title-color);
    color: var(--other-color);
    transition: ease 150ms;
  }
  
  .btn.--primary:hover {
    background-color: var(--title-color);
    color: var(--other-color);
    border: 1px solid var(--title-color);
  }
  
  /* Hover styles */
  .btn.--primary:hover {
    background-color: var(--title-color);
    border: 1px solid var(--highlight-color);
    transform: scale(1.05);
  }
  
  /* Outer glow on hover */
  .btn.--primary:hover::after {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border-radius: inherit;
    box-shadow: 0 0 1rem 0.5rem var(--highlight-color);
    opacity: 0.6;
  }
  
  
  .k_ui_toggle_switch.--enabled .k_ui_toggle_switch_bar {
    background: var(--highlight-color);
    background: linear-gradient(90deg, var(--highlight-color), var(--highlight-color));
    box-shadow: 0 0 0 1px var(--highlight-color);
  }
  
.serp-nav .nav_item.n_se:after,
.serp-nav .nav_item.n_im:after,
.serp-nav .nav_item.n_vi:after,
.serp-nav .nav_item.n_ne:after,
.serp-nav .nav_item.n_ma:after {
  background-color: var(--highlight-color);
}
  
  
  .landing-category-select .landing_cat_buttons>button.n_se.--active, .landing-category-select .landing_cat_buttons>button.n_se:hover {
    border-bottom: solid var(--highlight-color);
    color: var(--text-color);
  }
  
  .landing-category-select .landing_cat_buttons>button.n_ne.--active, .landing-category-select .landing_cat_buttons>button.n_ne:hover {
      border-bottom: solid var(--highlight-color);
    color: var(--text-color);
  }
  
  .landing-category-select .landing_cat_buttons>button.n_ma.--active, .landing-category-select .landing_cat_buttons>button.n_ma:hover {
      border-bottom: solid var(--highlight-color);
    color: var(--text-color);
  }
  
  .landing-category-select .landing_cat_buttons>button.n_vi.--active, .landing-category-select .landing_cat_buttons>button.n_vi:hover {
      border-bottom: solid var(--highlight-color);
    color: var(--text-color);
  }
  
  .landing-category-select .landing_cat_buttons>button.n_im.--active, .landing-category-select .landing_cat_buttons>button.n_im:hover {
      border-bottom: solid var(--highlight-color);
    color: var(--text-color);
  }
  
  .k_ui_dropdown.__basic .k_ui_dropdown_data_list .list_items>a, .k_ui_dropdown.__basic .k_ui_dropdown_data_list .list_items>label {
    color:var(--text-color);
  }
  
.quick-search-btn svg {
  color: var(--other-color);
}

.quick-search-btn{
  background:var(--highlight-color);
  backgroud-color:var(--highlight-color);
}
  
/* mobile buttons */

.mob .landing-category-select .landing_cat_buttons > button.--active {
  border: 1px solid var(--highlight-color);
  background-color: var(--highlight-color); 
  color: var(--text-color);}
```
