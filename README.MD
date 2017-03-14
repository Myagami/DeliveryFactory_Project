# About
シムトラに宅配便産業を

## 各種アドオン説明

* Office

> Delivery_Office(Out) / 営業所(発送)
>> 生産:小口荷物
>
> Delivery_Office(In) / 営業所(配送)
>> 消費:小口荷物

* District_Base

> Delivery_DistrictBase(Out) / 地区物流センター(発送)
>> 生産:地区カーゴ
>>
>> 消費:小口荷物
>
> Delivery_DistrictBase(In) / 地区物流センター(配送)
>> 生産:小口荷物
>>
>> 消費:地区カーゴ

* TrunkLine_Base

> Delivery_TrunkLine_Base(Out) / 主要物流センター(発送)
>> 生産:幹線カーゴ
>>
>> 消費:地区カーゴ
>
> Delivery_TrunkLine_Base(In) / 主要物流センター(配送)
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

## Extensions
拡張アドオンについては以下のページの参照を強くおすすめします

[Extension](https://github.com/Myagami/DeliveryFactory_Project/tree/master/Extensions)

## Convert
既存の産業のフローに組み込むために
> 各種変換用のアドオンを自分でこしらえてください

