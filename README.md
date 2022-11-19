# OverwatchUI

## Description
Some UI components designed by imitating Overwatch.

## Usage
```
https://raw.githubusercontent.com/CairBin/OverwatchUI/main/main.css
```
You can use CDN.
```
https://cdn.jsdelivr.net/gh/CairBin/OverwatchUI@v1.0/main.css
```

## Components

### button
```html
	<button class="ow-button ow-cancel-button">No</button>
    <button class="ow-button ow-ensure-button">Yes</button>
```

### menu
```html
	<div class="ow-ensure-menu">
        <div class="ow-ensure-menu-title">Exit？</div>
        <div class="ow-ensure-menu-option">
            <button class="ow-button ow-cancel-button">No</button>
            <button class="ow-button ow-ensure-button">Yes</button>
        </div>
    </div>
```

### card
```html
	<div class="ow-card">
        <img src="https://img.zmtc.com/2020/0211/20200211084406659.jpg" class="ow-card-img">
		<div class="ow-card-title">
            Title
		</div>
        <div class="ow-card-text">
			Hello,World
        </div>
    </div>
```

### tips and split-line
```html
	<div class="ow-tip">
        <div>tips</div>
        <div class="ow-ver-split-line"></div>
        <div>This is a test</div>
    </div>
```

### avatar
```html
	<img class="ow-avatar" src="https://img.zmtc.com/2020/0211/20200211084406659.jpg">
```

### list
```html
	<div class="ow-list">
        <div class="ow-list-item">
			<div class="ow-list-item-title">
                item
            </div>
        </div>
        <div class="ow-list-item ow-list-item-selected">
            <div class="ow-list-item-title">
                item-selected
            </div>
        </div>
    </div>
```

### layout

```html
	<div class="ow-nav">
        <!-- To Do -->
    </div>
	
	<div class="ow-content">
	    <!-- To Do -->
	</div>
	
	<div class="ow-footer">
        &copy; Copyright XXXXX XXXX-XXXX
    </div>
````
