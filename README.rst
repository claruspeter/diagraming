Readme as an RST
================


.. image:: http://yuml.me/diagram/scruffy/class/  
  [sites]<>-Wap[wap-aquifer-test],
  [sites]<>-Wap[wap-sd],
  [sites]<>-poly_join(GwSpatialUnitId.CWAZ)[gw-zones],
  [sites]-kd_nearest(linear_nodes)[sw-zones],

.. image::https://g.gravizo.com/svg?
  digraph G {
     main -> parse -> execute;
     main -> init;
     main -> cleanup;
     execute -> make_string;
     execute -> printf
     init -> make_string;
     main -> printf;
     execute -> compare;
   }


Other Examples
--------------

.. image:: http://yuml.me/diagram/scruffy/activity/
  (start)-><a>[kettle empty]->(Fill Kettle)->|b|,
  <a>[kettle full]->|b|->(Boil Kettle)->|c|,
  |b|->(Add Tea Bag)->(Add Milk)->|c|->(Pour Water)->(end),
  (Pour Water)->(end)

.. image:: http://yuml.me/diagram/scruffy/class/  
  [note: You can stick notes on diagrams too!{bg:wheat}],
  [Customer]<>1-orders 0..*>[Order],
  [Order]++*-*>[LineItem],
  [Order]-1>[DeliveryMethod],
  [Order]*-*>[Product],
  [Category]<->[Product],
  [DeliveryMethod]^[National],
  [DeliveryMethod]^[International]
