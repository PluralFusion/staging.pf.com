---
title: "Product"
description: "this is meta description"
bg_image: "images/product-bg.jpg"
layout: "service"
draft: true

########################### about service #############################
about:
  enable : true
  title : "Creative UX/UI Design Agency"
  content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptate soluta corporis odit, optio
          cum! Accusantium numquam ab, natus excepturi architecto earum ipsa aliquam, illum, omnis rerum, eveniet
          officia nihil. Eum quod iure nulla, soluta architecto distinctio. Nesciunt odio ullam expedita, neque fugit
          maiores sunt perferendis placeat autem animi, nihil quis suscipit quibusdam ut reiciendis doloribus natus nemo
          id quod illum aut culpa perspiciatis consequuntur tempore? Facilis nam vitae iure quisquam eius harum
          consequatur sapiente assumenda, officia voluptas quas numquam placeat, alias molestias nisi laudantium
          nesciunt perspiciatis suscipit hic voluptate corporis id distinctio earum. Dolor reprehenderit fuga dolore
          officia adipisci neque!"
  image : "images/company/company-group-pic.jpg"


########################## featured service ############################
featured_service:
  enable : true
  service_item:
    # featured service item loop
    - name : "Interface Design"
      icon : "fas fa-flask"
      color : "primary"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."

    # featured service item loop
    - name : "Product Branding"
      icon : "fas fa-leaf"
      color : "primary-dark"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."
  
    # featured service item loop
    - name : "Game Development"
      icon : "fas fa-lightbulb"
      color : "primary-darker"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."


############################# Service ###############################
service:
  enable : true
  title : "Products & Services"
  description : "We develop highly efficient, secure and affordable health & safety solutions for consumers, brands and industries."
  service_item:
    # service item loop
    - icon : fas fa-microchip #https://fontawesome.com/v6.7.2/icons
      name: Connected Devices
      content: "Branded, integrated health and safety devices"

    # service item loop
    - icon : fas fa-mobile-screen #https://fontawesome.com/v6.7.2/icons
      name: Applications
      content: "Device-connected and consumer-facing apps that foster healthy living"

      # service item loop
    - icon : fas fa-layer-group #https://fontawesome.com/v6.72/icons
      name: Health & Safety Platform
      content: "Device integration, data security, and ongoing support"

    # service item loop
    - icon : fas fa-code #https://fontawesome.com/v6.7.2/icons
      name: Development & Integration 
      content: "Delivering innovative, scalable and reliable solutions"

    # # service item loop
    # - icon : fas fa-worm #https://fontawesome.com/v6.7.2/icons
    #   name: Brand Identity
    #   content: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut"

    # # service item loop
    # - icon : fas fa-feather #https://fontawesome.com/v5.15/icons
    #   name: Brand Identity
    #   content: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut"

############################# call to action #################################
cta:
  enable : true
  # call to action content comes from "_index.md"
---
