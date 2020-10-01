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
4. [Resources](#resources-en)

# 目次

1. [ウェブアプリケーションについて](#general-ja)
2. [場所を表示する](#displaying-spots-ja)
3. [場所を追加する](#adding-a-spot-ja)
  * [地図上で場所を選択する](#spot-selection-ja)
4. [資料](#resources-ja)

<br>

## General remarks<a name="general-en"></a>

When entering the application, you will be greeted by this view:

![Front-en](../assets/img/front_en.png)

By clicking on "Explore" you will be led to the main spots view. You will also be able to choose the UI language between English and Japanese. Furthermore, below you will find general information on the project as well as a small map showing all the places in the database.

Entering the app gives you the full map view with all the literary spots currently in store:

![All-spots-en](../assets/img/all_spots_en.png)

You can click on any one spot to reveal some additional information in an overlay:

![Overlay-en](../assets/img/spot_overlay_en.png)

From the overlay, you can also access the detailed spot page (see [next section](#displaying-spots-en)). Furthermore, there are four interaction buttons on the top left of the map view:

![Buttons](../assets/img/all_spots_buttons.png)

They allow you to zoom in or out of the map (although you can do this with your mouse or trackpad as well), make the map fullscreen, or switch to a tabular view of the spots. When clicking the last button, all spots are shown in a table as follows:

![All-spots-table-en](../assets/img/all_spots_table_en.png)

In the table view, you can access the detailed spot page and also filter spots by their name by using the search bar. You can switch back to the map view by clicking the button on the top left of the table view:

![Map-switch-en](../assets/img/map_switch_en.png)

Lastly, if you are a user who has access to the database, you can log in after entering the main app. The header section includes a menu symbol that when clicked reveals the following links:

![Menu-en](../assets/img/menu_en.png)

From there, you can reach the login page. Note that you can also at any point in time switch languages via the menu.

### Note

In the foreseeable future, the front page will be expanded to include an explanation as to how spot and poem data is assembled.

## Displaying spots<a name="displaying-spots-en"></a>

Once you access a spot's detail page (either via the map overlay or the spots table), you will see the first of four tabs:

![Spot-detail-en](../assets/img/spot_detail/spot_detail_en.png)

The "Basic information" tab shows a miniature map with the selected place and information on its name (in Kanji, Furigana, and Romaji), historic Kuni 国, current prefecture 県, as well as its latitude and longitude. Furthermore, the tab provides information on whether the place is an utamakura 歌枕 or not, and whether it is a meisho 名所 or not.

If the place is an utamakura, there will furthermore be information on its meaning, features, and associations. Lastly, there is a field called "Keywords":

![Spot-detail-keywords-en](../assets/img/spot_detail/spot_detail_keywords_en.png)

As we will shortly see, each literary reference to the spot (e.g. in a poem) invokes the spot with a different form; i.e. in one case the spot can simply be referenced by its name, in another by a creek in that spot, and in yet another by a bridge in that spot. The "Keywords" field in the "Basic information" tab simply serves to summarize all possible variants of this spot as it has been used in literature.

The next tab concerns a spot's topography and history as these are important determinants for its literary and cultural significance:

![Spot-detail-history-en](../assets/img/spot_detail/spot_detail_history_en.png)

Note that in the future, the fields "topography" and "history" will be split into an English and a Japanese version of each, so that it becomes easier to distinguish information in each language.

The third tab, "Poetry", shows all poems from a selection of poetry collections (see [Resources](#resources-en)) that make reference to the particular spot:

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

## Resources<a name="resources-en"></a>

We currently use eight main resources for the literature, specifically poems, to select for the spots. The eight resources are:

  * 古今和歌集 Kokin wakashū
  * 後撰和歌集 Gosen wakashū
  * 拾遺和歌集 Shūi wakashū
  * 後拾遺和歌集 Goshūi wakashū
  * 金葉和歌集 Kin'yō wakashū
  * 詞花和歌集 Shika wakashū
  * 千載和歌集 Senzai wakashū
  * 新古今和歌集 Shinkokin wakashū

<br>

---

<br>

## ウェブアプリケーションについて<a name="general-ja"></a>

When entering the application, you will be greeted by this view:

![Front-ja](../assets/img/front_ja.png)

By clicking on "Explore" you will be led to the main spots view. You will also be able to choose the UI language between English and Japanese. Furthermore, below you will find general information on the project as well as a small map showing all the places in the database.

Entering the app gives you the full map view with all the literary spots currently in store:

![All-spots-ja](../assets/img/all_spots_ja.png)

You can click on any one spot to reveal some additional information in an overlay:

![Overlay-ja](../assets/img/spot_overlay_ja.png)

From the overlay, you can also access the detailed spot page (see [next section](#displaying-spots-en)). Furthermore, there are four interaction buttons on the top left of the map view:

![Buttons](../assets/img/all_spots_buttons.png)

They allow you to zoom in or out of the map (although you can do this with your mouse or trackpad as well), make the map fullscreen, or switch to a tabular view of the spots. When clicking the last button, all spots are shown in a table as follows:

![All-spots-table-ja](../assets/img/all_spots_table_ja.png)

In the table view, you can access the detailed spot page and also filter spots by their name by using the search bar. You can switch back to the map view by clicking the button on the top left of the table view:

![Map-switch-ja](../assets/img/map_switch_ja.png)

Lastly, if you are a user who has access to the database, you can log in after entering the main app. The header section includes a menu symbol that when clicked reveals the following links:

![Menu-ja](../assets/img/menu_ja.png)

From there, you can reach the login page. Note that you can also at any point in time switch languages via the menu.

### Note

In the foreseeable future, the front page will be expanded to include an explanation as to how spot and poem data is assembled.

## 場所を表示する<a name="displaying-spots-ja"></a>

Once you access a spot's detail page (either via the map overlay or the spots table), you will see the first of four tabs:

![Spot-detail-ja](../assets/img/spot_detail/spot_detail_ja.png)

The "Basic information" tab shows a miniature map with the selected place and information on its name (in Kanji, Furigana, and Romaji), historic Kuni 国, current prefecture 県, as well as its latitude and longitude. Furthermore, the tab provides information on whether the place is an utamakura 歌枕 or not, and whether it is a meisho 名所 or not.

If the place is an utamakura, there will furthermore be information on its meaning, features, and associations. Lastly, there is a field called "Keywords":

![Spot-detail-keywords-ja](../assets/img/spot_detail/spot_detail_keywords_ja.png)

As we will shortly see, each literary reference to the spot (e.g. in a poem) invokes the spot with a different form; i.e. in one case the spot can simply be referenced by its name, in another by a creek in that spot, and in yet another by a bridge in that spot. The "Keywords" field in the "Basic information" tab simply serves to summarize all possible variants of this spot as it has been used in literature.

The next tab concerns a spot's topography and history as these are important determinants for its literary and cultural significance:

![Spot-detail-history-ja](../assets/img/spot_detail/spot_detail_history_ja.png)

Note that in the future, the fields "topography" and "history" will be split into an English and a Japanese version of each, so that it becomes easier to distinguish information in each language.

The third tab, "Poetry", shows all poems from a selection of poetry collections (see [Resources](#resources-en)) that make reference to the particular spot:

![Spot-detail-poems-ja](../assets/img/spot_detail/spot_detail_poems_ja.png)

All associated poems are shown in a table, and clicking on one reveals more detailed information on it:

![Spot-detail-one-poem-ja](../assets/img/spot_detail/spot_detail_one_poem_ja.png)

This window shows from which resource the poem comes from (e.g. 新古今和歌集), the identifier within that resource (e.g. 新古今 883), the volume of the resource, its preface (kotobagaki 詞書), its actual text, the form used to reference the spot ("Keyword", see above), the author, and a link to a scanned resource from the National Institute for Japanese Literature (NIJL).

Lastly, next to the original text itself you will find a button to display a Romaji transliteration of the text:

![Spot-detail-one-poem-romaji-ja](../assets/img/spot_detail/spot_detail_one_poem_romaji_ja.png)

### Note

In the foreseeable future, we will add a IIIF viewer to the poem windows in order to show a preview of the document linked to the NIJL database.

## 場所を追加する<a name="adding-a-spot-ja"></a>

Relevant to project members is the ability to add new spots to the database. Once you are logged in, you can add spots in two ways. The first is to click on the new "+" button in the map view of the spots:

![Add-spot-map](../assets/img/add_spot/add_spot_map.png)

The other is to click the "Add spot" button on the top right of the table view:

![Add-spot-table-ja](../assets/img/add_spot/add_spot_table_ja.png)

Clicking on either one of the buttons gives you the view to add a new spot:

![Add-spot-ja](../assets/img/add_spot/add_spot_ja.png)

The view itself is structured the same way as the view for [displaying a spot](#displaying-spots-en). However, the miniature map view now shows all spots on the map as well. This is so as to have a reference to previous spots when adding a new one.

Since most information is the same as we have already seen (history, spots etc.), we will only focus our attention here on how to select a new spot itself.

### 地図上で場所を選択する<a name="spot-selection-ja"></a>

There are two ways you can select a new spot. The first is to simply double-click on the map. The app then adds a red marker to the map and gathers its latitude and longitude. In addition, depending on your zoom level, the app also tries to find the nearest place automatically and fill out its name:

![Add-spot-double-click-ja](../assets/img/add_spot/add_spot_double_click_ja.png)

The second way is using the search button on the top left of the miniature map. Note that once a spot is selected, the search button disappears. You first have to click on the marker to remove it and thus make the search button reappear. Then, clicking on search opens a small search window where you can type in the spot to be added:

![Add-spot-search-ja](../assets/img/add_spot/add_spot_search_ja.png)

The app will show you some suggestions and clicking on one automatically adds a marker and fills in some basic information:

![Add-spot-select-ja](../assets/img/add_spot/add_spot_select_ja.png)

In both cases, if you are not satisfied with the placement of the marker or the associated place name, you can manually move the marker around on the map (automatically updating latitude and longitude) and manually edit the spot name information. 

## 資料<a name="resources-ja"></a>

We currently use eight main resources for the literature, specifically poems, to select for the spots. The eight resources are:

  * 古今和歌集
  * 後撰和歌集
  * 拾遺和歌集
  * 後拾遺和歌集
  * 金葉和歌集
  * 詞花和歌集
  * 千載和歌集
  * 新古今和歌集