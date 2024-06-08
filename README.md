# Strength Moves Mountains

<div align="center" style="font-size: 22px; font-weight: bold;">
    Strength Moves Mountains
</div>

## Background Examples

Below are examples of how to use various backgrounds in your HTML.

### Full Background

This example sets a full-page background image with semi-transparency.

```html
<div style="
        pointer-events: none;
        z-index: -10;
        position: fixed;
        top: 0;
        left: 0;
        height: 100vh;
        width: 100vw;
        opacity: 0.5;
        background: url('https://raw.githubusercontent.com/KinoThe-Kafkaesque/KinoThe-Kafkaesque/main/strength.jpg') no-repeat center center;
        background-size: cover;
        ">
</div>
<div style="
        pointer-events: none;
        z-index: -9;
        position: fixed;
        bottom: 0;
        right: 0;
        height: 200px;
        width: 200px;
        opacity: 1;
        background: url('https://raw.githubusercontent.com/KinoThe-Kafkaesque/KinoThe-Kafkaesque/main/nero.gif') no-repeat 10% 10%; 
        background-size: contain;
        ">
</div>
<div style="
        pointer-events: none;
        z-index: 10;
        position: fixed;
        top: 20vh;
        left: 0;
        height: 60vh;
        width: 20vw;
        opacity: 1;
        background: url('https://raw.githubusercontent.com/KinoThe-Kafkaesque/KinoThe-Kafkaesque/main/shiki.png') no-repeat center center; 
        background-size: contain;
        ">
</div>
<div style="
        pointer-events: none;
        z-index: 10;
        position: fixed;
        top: 20vh;
        left: 0;
        height: 60vh;
        width: 180vw;
        opacity: 1;
        background: url('https://raw.githubusercontent.com/KinoThe-Kafkaesque/KinoThe-Kafkaesque/main/shiki.gif') no-repeat center center; 
        background-size: contain;
        ">
</div>
