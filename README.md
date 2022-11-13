```mermaid
graph TD;
    CB[Capture-Board]
    click CB "https://www.amazon.co.jp/gp/product/B08P2NQCX8/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1"
    HS[HDMI-Selector]
    click HS "https://www.amazon.co.jp/gp/product/B075L69WRR/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1"
    BR[Bluetooth-Reciever]
    click BR "https://www.amazon.co.jp/gp/product/B01KTENVK2/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1"
    Mixer
    click Mixer "https://www.amazon.co.jp/gp/product/B07DRCLCNL/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1"
    BR-->Mixer
    Switch-->CB
    CB-->Mixer
    CB-->HS
    Mic-->PC
    Camera-->PC
    PC-->Mixer
    PC-->HS
    Mac-->HS
    Mixer-->Speaker
    Mixer-->Head-Phone
    HS-->Monitor1
    HS-->Monitor2
```
