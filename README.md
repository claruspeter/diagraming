# diagraming


```mermaid
    erDiagram
      sites ||--o| wap-aquifer-test : Wap
      sites ||--o| wap-sd : Wap
      sites ||--o| gw-zones: "poly_join(GwSpatialUnitId.CWAZ)"
      sites ||--|| sw-zones: "kd_nearest(linear nodes)"
```


![yml.me](http://yuml.me/diagram/scruffy/class/[note: You can stick notes on diagrams too!{bg:wheat}],[Customer]<>1-orders 0..*>[Order], [Order]++*-*>[LineItem], [Order]-1>[DeliveryMethod], [Order]*-*>[Product], [Category]<->[Product], [DeliveryMethod]^[National], [DeliveryMethod]^[International])
