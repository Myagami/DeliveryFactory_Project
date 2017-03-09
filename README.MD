# About
シムトラに宅配便産業を

## ディレクトリ説明

* Office

> 営業所(発送)
>> 生産:小口荷物
>
> 営業所(配送)
>> 消費:小口荷物

* District_Base

> 地区物流センター(発送)
>> 生産:地区カーゴ
>>
>> 消費:小口荷物
>
> 地区物流センター(配送)
>> 生産:小口荷物
>>
>> 消費:地区カーゴ

* TrunkLine_Base

> 主要物流センター(発送)
>> 生産:幹線カーゴ
>>
>> 消費:地区カーゴ
>
> 主要物流センター(配送)
>> 生産:地区カーゴ
>>
>> 消費:幹線カーゴ

## 貨物一覧

* Delivery_Box(Small) / 小口荷物

> 営業所と地区物流センター間とやりとりします
>> 単位:box / 箱

* Delivery_Box(District) / 地区カーゴ

> 単位:Cargo / カーゴ
>> 地区物流センター間や主要物流センター間とでやり取りします

* Delivery_Box(Trunk) / 幹線カーゴ

> 単位:Cargo / カーゴ
>> 主要物流センター間でやり取りします

## 産業フロー

![フロー](https://raw.githubusercontent.com/Myagami/DeliveryFactory_Project/master/Delivery_Flow.png)
##
