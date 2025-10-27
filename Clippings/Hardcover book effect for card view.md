https://gist.github.com/kepano/8afc4cad9c32f4fde6ef6347f66a0571
https://www.reddit.com/r/ObsidianMD/comments/1ogpxtg/hardcover_book_effect_for_card_view/

```css
/* Hardcover book cover effect for card views in Obsidian Bases */

.bases-view {
  --bases-cards-background: transparent;
  --bases-cards-cover-background: transparent;
  --bases-cards-shadow: none;
  --bases-cards-shadow-hover: none;
}
.bases-cards-group {
  gap: 20px;
  padding: 20px;
}
.bases-cards-label {
  display: none;
}
.bases-cards-item {
  overflow: visible;
  gap: 0px;
  contain: inherit;
}
.bases-cards-property.mod-title {
  padding-top: 10px;
}

/* Book shadow */
.bases-cards-cover {
  transition: transform 0.1s ease-out, box-shadow 0.1s ease-out;
  border-radius: 2px 6px 6px 2px;
  box-shadow: inset 1px 1px 0 1px rgba(255,255,255,0.2), inset 0 0 0 1px rgba(0,0,0,0.1), -4px 2px 4px 0 rgba(0,0,0,0.3), -8px 8px 20px 0 rgba(0,0,0,0.2);
}

/* Book spine effect */
.bases-cards-cover:before {
  content: "";
  background-image: linear-gradient(to right, rgba(0,0,0,0.2), rgba(255,255,255,0.3) 1%, transparent 6%, rgba(0,0,0,0.15) 8%, rgba(255,255,255,0.2) 9%, transparent 20%);
  width: 100%;
  position: absolute;
  height: 100%;
}
.bases-cards-item:hover .bases-cards-cover {
  transform: translateY(-4px) scale(1.03);
  box-shadow: inset 1px 1px 0 1px rgba(255,255,255,0.2), inset 0 0 0 1px rgba(0,0,0,0.1), -4px 4px 8px 0 rgba(0,0,0,0.3), -12px 16px 30px 0 rgba(0,0,0,0.3);
}

/* Show title on two lines */
.bases-cards-property.mod-title .bases-cards-line {
  font-size: var(--font-ui-small);
  line-height: 1.2;
  height: 2.8em;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: normal;
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
}
```