---
layout: page
title: User Guide
subtitle: サイト閲覧凡例
---

# Contents

1. [General remarks](#general-en)
2. [Displaying spots](#displaying-spots-en)
3. [Adding a new spot](#adding-a-spot-en)
  * [Selecting a spot on the map](#spot-selection-en)

# 目次

1. [ウェブアプリケーションについて](#general-ja)
2. [場所を表示する](#displaying-spots-ja)
3. [場所を追加する](#adding-a-spot-ja)
  * [地図上で場所を選択する](#spot-selection-ja)

<br>

## General remarks<a name="general-en"></a>

When entering the application, you will be greeted by this view:

![Front-en](../assets/img/front_en.png)

You will also be able to choose the UI language between English and Japanese. Furthermore, below you will find general information on the project as well as a small map showing all the places in the database.

Importantly, the front page includes explanatory notes:

![Explanatory-notes-en](../assets/img/explanatory_notes_en.png)

These explanatory notes serve to summarize the process of gathering and inputting data for the spots and literary references. They are divided by category, so that you can access these notes from the spot display view (see [next section](#displaying-spots-en)) per category as well.

By clicking on "Explore" you will be led to the main spots view. Entering the app gives you the full map view with all the literary spots currently in store:

![All-spots-en](../assets/img/all_spots_en.png)

You can click on any one spot to reveal some additional information in an overlay:

![Overlay-en](../assets/img/spot_overlay_en.png)

From the overlay, you can also access the detailed spot page (see [next section](#displaying-spots-en)). Furthermore, there are four interaction buttons on the top left of the map view:

![Buttons](../assets/img/all_spots_buttons.png)

They allow you to zoom in or out of the map (although you can do this with your mouse or trackpad as well), make the map fullscreen, or switch to a tabular view of the spots. When clicking the last button, all spots are shown in a table as follows:

![All-spots-table-en](../assets/img/all_spots_table_en.png)

In the table view, you can access the detailed spot page and also filter spots by their name by using the search bar. You can switch back to the map view by clicking the button on the top left of the table view:

![Map-switch-en](../assets/img/map_switch_en.png)

## Displaying spots<a name="displaying-spots-en"></a>

Once you access a spot's detail page (either via the map overlay or the spots table), you will see the first of four tabs:

![Spot-detail-en](../assets/img/spot_detail/spot_detail_en.png)

The "Basic information" tab shows a miniature map with the selected place and information on its name (in Kanji, Furigana, and Romaji), historic Kuni 国, current prefecture 県, as well as its latitude and longitude. Furthermore, the tab provides information on whether the place is an utamakura 歌枕 or not, and whether it is a meisho 名所 or not.

If the place is an utamakura, there will furthermore be information on its meaning, features, and associations. Lastly, there is a field called "Keywords":

![Spot-detail-keywords-en](../assets/img/spot_detail/spot_detail_keywords_en.png)

As we will shortly see, each literary reference to the spot (e.g. in a poem) invokes the spot with a different form; i.e. in one case the spot can simply be referenced by its name, in another by a creek in that spot, and in yet another by a bridge in that spot. The "Keywords" field in the "Basic information" tab simply serves to summarize all possible variants of this spot as it has been used in literature.

The next tab concerns a spot's topography and history as these are important determinants for its literary and cultural significance:

![Spot-detail-history-en](../assets/img/spot_detail/spot_detail_history_en.png)

The third tab, "Poetry", shows all poems from a selection of poetry collections that make reference to the particular spot:

![Spot-detail-poems-en](../assets/img/spot_detail/spot_detail_poems_en.png)

All associated poems are shown in a table, and clicking on one reveals more detailed information on it:

![Spot-detail-one-poem-en](../assets/img/spot_detail/spot_detail_one_poem_en.png)

This window shows from which resource the poem comes from (e.g. 新古今和歌集), the identifier within that resource (e.g. 新古今 883), the volume of the resource, its preface (kotobagaki 詞書), its actual text, the form used to reference the spot ("Keyword", see above), the author, and a link to a scanned resource from the National Institute for Japanese Literature (NIJL).

Lastly, next to the original text itself you will find a button to display a Romaji transliteration of the text:

![Spot-detail-one-poem-romaji-en](../assets/img/spot_detail/spot_detail_one_poem_romaji_en.png)

### Note

In the foreseeable future, we will add a IIIF viewer to the poem windows in order to show a preview of the document linked to the NIJL database.

## Adding a spot<a name="adding-a-spot-en"></a>

Relevant to project members is the ability to add new spots to the database. Once you are logged in, you can add spots in two ways. The first is to click on the new "+" button in the map view of the spots:

![Add-spot-map](../assets/img/add_spot/add_spot_map.png)

The other is to click the "Add spot" button on the top right of the table view:

![Add-spot-table-en](../assets/img/add_spot/add_spot_table_en.png)

Clicking on either one of the buttons gives you the view to add a new spot:

![Add-spot-en](../assets/img/add_spot/add_spot_en.png)

The view itself is structured the same way as the view for [displaying a spot](#displaying-spots-en). However, the miniature map view now shows all spots on the map as well. This is so as to have a reference to previous spots when adding a new one.

Since most information is the same as we have already seen (history, spots etc.), we will only focus our attention here on how to select a new spot itself.

### Selecting a spot on the map<a name="spot-selection-en"></a>

There are two ways you can select a new spot. The first is to simply double-click on the map. The app then adds a red marker to the map and gathers its latitude and longitude. In addition, depending on your zoom level, the app also tries to find the nearest place automatically and fill out its name:

![Add-spot-double-click-en](../assets/img/add_spot/add_spot_double_click_en.png)

The second way is using the search button on the top left of the miniature map. Note that once a spot is selected, the search button disappears. You first have to click on the marker to remove it and thus make the search button reappear. Then, clicking on search opens a small search window where you can type in the spot to be added:

![Add-spot-search-en](../assets/img/add_spot/add_spot_search_en.png)

The app will show you some suggestions and clicking on one automatically adds a marker and fills in some basic information:

![Add-spot-select-en](../assets/img/add_spot/add_spot_select_en.png)

In both cases, if you are not satisfied with the placement of the marker or the associated place name, you can manually move the marker around on the map (automatically updating latitude and longitude) and manually edit the spot name information. 

<br>

---

<br>

## ウェブアプリケーションについて<a name="general-ja"></a>

アプリケーションをアクセスしますと、次の画面が表示されます：

![Front-ja](../assets/img/front_ja.png)

このページでは、UIの言語を切替えることができます（選択肢は日本語と英語です）。プロジェクトに関する情報などもフロントページにあります。何よりも先ず、プロジェクトの作業凡例がフロントページに記載されてます：

![Explanatory-notes-ja](../assets/img/explanatory_notes_ja.png)

この作業凡例にて、場所・和歌等のデータの収集・記入についての情報がまとめられてます。カテゴリーに分類されてるため、場所を表示する画面でも（項目[「場所を表示する」](#displaying-spots-ja)）、カテゴリーごとに凡例を閲覧することができます。

尚、フロントページの「閲覧する」をクリックしますと、DLMのメイン地図が表示されます。この地図は、DLM内の全場所を同時に地図上で表示します：

![All-spots-ja](../assets/img/all_spots_ja.png)

各場所をクリックできますが、一つの場所を選びますと、追加情報が以下の通りに、オーバーレイで表示されます：

![Overlay-ja](../assets/img/spot_overlay_ja.png)

このオーバーレイからは、場所の詳細ページを開くことができます（項目[「場所を表示する」](#displaying-spots-ja)）。更に、地図上の左上に四つのボタンがあります：

![Buttons](../assets/img/all_spots_buttons.png)

このボタンで、地図のズーム（マウス、又はトラックパッドでも可能）、地図のフルサイズ化、又は場所のテーブル表示を選択できます。最後のボタンをクリックしますと、場所は以下のようにテーブルで表示されます：

![All-spots-table-ja](../assets/img/all_spots_table_ja.png)

テーブル表示からも、場所の詳細ページを開くことができますし、地名で場所を検索することもできます。地図表示に戻るには、左上の「地図表示」ボタンをクリックするので充分です：

![Map-switch-ja](../assets/img/map_switch_ja.png)

## 場所を表示する<a name="displaying-spots-ja"></a>

場所の詳細ページを開きますと、４つのタブの内の、次の「基本情報」というタブが表示されます：

![Spot-detail-ja](../assets/img/spot_detail/spot_detail_ja.png)

「基本情報」タブには、選択した場所を表示する小型地図と、場所の地名（漢字、ふりがな、ローマ字）、国、都道府県、そして経緯度が記載されています。更に、その場所は歌枕であるか、又は名所であるか、との情報も含められています。

歌枕であれば、歌枕としての意味と特徴、更に歌枕として何を呼び起こしているか（連想）、についての情報も表示されます。最後に、「キーワード」という項目があります：

![Spot-detail-keywords-ja](../assets/img/spot_detail/spot_detail_keywords_ja.png)

「キーワード」とは、各和歌等で、その場所を表す言葉を示しています。例えば、ある和歌では、場所は単に地名で表されるかもしれませんが、別の和歌では、その場所に属する浦・橋等で表現されることがあります。「基本情報」の「キーワード」項目は、この場合多数の表現をまとめて表示するためです。

次のタブは、場所の地誌と歴史についての情報をまとめてます：

![Spot-detail-history-ja](../assets/img/spot_detail/spot_detail_history_ja.png)

三つ目の「和歌・漢詩・俳諧」タブは、資料で現れる、選択した場所を表現する和歌等をテーブルで表示します：

![Spot-detail-poems-ja](../assets/img/spot_detail/spot_detail_poems_ja.png)

各エントリーをクリックしますと、そのエントリーの詳細情報が現れます：

![Spot-detail-one-poem-ja](../assets/img/spot_detail/spot_detail_one_poem_ja.png)

このウィンドウでは、次の情報が記載されてます。資料（例えば、新古今和歌集）、ID（国歌大観番号、例えば、新古今 883）、資料の巻・部立、詞書、テクスト自体、キーワード、著者、そして国文学研究資料館（NIJL）がデジタル化した資料へのリンク。

最後に、テクストの隣のボタンで、ローマ字版を表示することができます:

![Spot-detail-one-poem-romaji-ja](../assets/img/spot_detail/spot_detail_one_poem_romaji_ja.png)

### 注意

近々、IIIFビューアーを導入し、NIJLの資料を以上のウィンドウで表示する予定です。

## 場所を追加する<a name="adding-a-spot-ja"></a>

プロジェクト関連者にとっては、場所を追加・編集する機能が必要です。ログイン後、場所を二つの方法で追加できます。一つ目は、場所の地図表示で、ログイン後に新しく追加された「＋」ボタンをクリックすることです：

![Add-spot-map](../assets/img/add_spot/add_spot_map.png)

もう一つの方法は、テーブル表示で、右上の「文学名所を追加」のボタンをクリックすることです：

![Add-spot-table-ja](../assets/img/add_spot/add_spot_table_ja.png)

クリック後、場所の追加画面が表示されます:

![Add-spot-ja](../assets/img/add_spot/add_spot_ja.png)

この画面は、[場所を表示する](#displaying-spots-ja)画面と同じ構造です。しかし、新しい場所を追加する時に、他の場所との関係性を表すためには、小型地図には全場所が表示されてます。

殆どの情報は場所を表示する時と同じですので、ここでは新しい場所自体を選択することを中心にしたいと思います。

### 地図上で場所を選択する<a name="spot-selection-ja"></a>

場所は、二つの方法で選択できます。一つ目は、単純に地図にダブルクリックすることです。そうしますと、赤いマーカーが追加され、地名と経緯度もアプリケーションから自動的に推定されます：

![Add-spot-double-click-ja](../assets/img/add_spot/add_spot_double_click_ja.png)

もう一つの方法は、小型地図の左上の検索ボタンを使うことです。赤いマーカーが表されている時は、検索ボタンは隠されますが、マーカーをクリックすることで、マーカーを削除し、検索ボタンを戻すことができます。検索ボタンをクリックしますと、小型の検索ウィンドウが現れます：

![Add-spot-search-ja](../assets/img/add_spot/add_spot_search_ja.png)

アプリケーションの提案のどれかを選びますと、自動的にマーカーと地名と経緯度が追加されます：

![Add-spot-select-ja](../assets/img/add_spot/add_spot_select_ja.png)

両方の場合、マーカーの位置や自動的に追加された地名に不満があれば、手動でマーカーを動かしたり、地名を編集できます。
