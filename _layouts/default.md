---
---

<!DOCTYPE html>
<html>
  <div class="container-fluid">
  
    {% include header.html %}

    <body>

      {% include nav.html %}

      <div class="container-fluid">
        <div class="row-fluid">
          <div class="carousel slide" id="myCarousel" data-interval="5000" data-ride="carousel">
            <div class="carousel-inner">

              <div class="item active">
                <ul class="thumbnails">
                  <li class="span6">
                    <div class="thumbnail">
                      <img src="{{ site.baseurl }}/images/ats-express.jpg" alt="">
                    </div>
                    <div class="caption">
                      <h5></h5>
                      
ATS Express Inc., formed in 1996, is a domestic freight forwarder with over 750 quality contracted carriers offering a variety of services nationwide such as LCL/LTL (less than truckload), TL (truckload), and intermodal cargo. Our strong relationships with our broad carrier base allow us to move any shipment, locally or nationwide with just a short notice. 

The high volume of cargo that we manage allows us great discounts that are passed on to our customers. We also offer transloading and freight consolidation within any city in the USA. But it doesn’t stop at the border, we deliver shipments to and from Canada also.

                    </div>
                  </li>
                </ul>
              </div>

              <div class="item">
                <ul class="thumbnails">
                  <li class="span3">
                    <div class="thumbnail">
                      <img src="{{ site.baseurl }}/images/ats-warehouse.jpg" alt="">
                    </div>
                    <div class="caption">
                      <h5></h5>

* ATS Warehouse, Inc. formed in 1986, began delivering lost luggage for the airlines that served the Charleston area. Today, 
* ATS Warehouse, Inc has over 50 employees servicing three public warehouses, utilizing over 270,000 square feet.

                    </div>
                  </li>
                </ul>
              </div>

              <div class="item">
                <ul class="thumbnails">
                  <li class="span3">
                    <div class="thumbnail">
                      <img src="{{ site.baseurl }}/images/ats-inter.jpg" alt="">
                    </div>
                    <div class="caption">
                      <h5></h5>
                    </div>
ATS Intermodal, LLC, formed in 1998, is a Transporation company specializing in Southeast freight. 
We handle the movement of containers from all ports, depots, rail yards and warehouses throughout the Southeast. 
ATS offers a growing fleet of over 60 trucks (48 asset-based) and a new fleet of 53' dry vans that allows us to accommodate even the largest of shippers.
                  </li>
                </ul>
              </div>

            </div>
            <a data-slide="prev" href="#myCarousel" class="left carousel-control">
              <span class="glyphicon glyphicon-chevron-left"></span>
            </a>
            <a data-slide="next" href="#myCarousel" class="right carousel-control">
              <span class="glyphicon glyphicon-chevron-right"></span>
            </a>
        </div>
      </div>
    </diV>
        {{ content }}
        {% include footer.html %}
        </div>
      </div>
      <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
      <script src="{{ site.baseurl }}/js/bootstrap.js"></script>
    </body>
  </div>

  



</html>
