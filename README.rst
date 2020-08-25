Readme as an RST
================


.. image:: http://yuml.me/diagram/scruffy/class/
  [Customer]->[Address2sdfsdf]
  
.. image:: http://yuml.me/diagram/scruffy/class/  
  [note: You can stick notes on diagrams too!{bg:wheat}],
  [Customer]<>1-orders 0..*>[Order],
  [Order]++*-*>[LineItem],
  [Order]-1>[DeliveryMethod],
  [Order]*-*>[Product],
  [Category]<->[Product],
  [DeliveryMethod]^[National],
  [DeliveryMethod]^[International]
