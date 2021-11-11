---
title: Dzīves cikla datu eksportēšanas norādījumi
description: Produkta dzīves cikla informācijas eksportēšana
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546863"
---
# <a name="lifecycle-data-export-guidance"></a>Dzīves cikla datu eksportēšanas norādījumi
Šajā dokumentā ir aprakstīts, kā izmantot produkta eksporta failu.

## <a name="query-information"></a>Informācija par vaicājumu
Dokumentā Excel ir iekļauti lauki, kas palīdz identificēt produktu tabulā aizpildītos datus.

### <a name="end-of-support"></a>Atbalsta beigu datums
Atbalsta beigu vērtība filtrē produktus pēc produkta atbalsta beigu datuma vai produkta laidiena beigu datuma.

Iespējamās vērtības: Visi (filtrs netiek lietots), Gads un Diapazons.

### <a name="family"></a>Saime
Saimes vērtība filtrē produktus pēc to pamatlīmeņa hierarhijā, ko dēvē par saimi.

Iespējamās vērtības: Visi (filtrs netiek lietots), Saimes nosaukums

### <a name="group"></a>Grupa
Grupas vērtība filtrē pamatlīmenī (saimē) iekļautos produktus pēc konkrētas grupas.

Iespējamās vērtības: Visi (filtrs netiek lietots), Grupas nosaukums

## <a name="table-columns"></a>Tabulas kolonnas
Produktu tabula sastāv no kolonnām, kas definē produktus, izdevumus, laidienus un atbilstošos atbalsta datumus.

> [!NOTE]
> Ir paredzēta rinda katram produktam, izdevumam un laidiena kombinācijai.

### <a name="product"></a>Produkts
Produkta nosaukums.

### <a name="edition"></a>Izdevums
Izdevumu kolonna tiek aizpildīta, ja produktam ir izdevumi. Ja produktam nav izdevumu, šis lauks ir tukšs.

### <a name="release"></a>Laidiens
Laidiena kolonna tiek aizpildīta, ja produktam ir vairāki laidieni.
Ja produktam ir tikai viens laidiens, šis lauks ir tukšs.

### <a name="support-policy"></a>Atbalsta politika
Šajā laukā ir norādīts, kādu atbalsta politika produkts ievēro.

Iespējamās vērtības: [Fiksētā](/lifecycle/policies/fixed), [Modernā](/lifecycle/policies/modern), Komponents

### <a name="start-date"></a>Sākuma datums
Datums, kurā sākta produkta atbalsta nodrošināšana.

### <a name="mainstream-date"></a>Standarta atbalsta datums
Ja atbalsta politika ir **Fiksētā** vai **Komponents**, šis ir produkta galvenā beigu datuma datums.
  
Ja atbalsta politika ir **Modernā**, šis lauks ir tukšs.

### <a name="extended-end-date"></a>Pagarinātais beigu datums
Ja atbalsta politika ir **Fiksētā** vai **Komponents**, šis ir datums, kad produkta beigu datums ir pagarināts.

Ja atbalsta politika ir **Modernā**, šis lauks ir tukšs.

### <a name="retirement-date"></a>Norakstīšanas datums
Ja atbalsta politika ir **Fiksētā** vai **Komponents**, šis lauks ir tukšs.

Ja atbalsta politika ir **Modernā**, šeit tiek norādīts produkta norakstīšanas datums.

### <a name="release-start-date"></a>Laidiena sākuma datums
Datums, kurā sākta laidiena atbalsta nodrošināšana. Ja produktam ir tikai viens laidiens, šis lauks ir tukšs.
 
### <a name="release-end-date"></a>Laidiena beigu datums
Laidiena atbalsta beigu datums.
Ja produktam ir tikai viens laidiens, šis lauks ir tukšs.

### <a name="docs-url"></a>Dokumentu vietrādis URL
Paplašinātās dokumentācijas vietrādis URL.
