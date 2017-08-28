Base Atomic CSS     
=============================

This is the start of the Base Atomic CSS for rapid prototyping. The idea behind this project is to provide a base set of utility classes that can be eaisily added to a new or existing project. It is designed to be modular so if you dont use a set of utility classes remove it from the import statement on the _utility-dir.scss file. 


This is a starter file that inludes: 
1. Jekyll 
2. Gulp
    Browser sync 
    Autoprefix
    Pug 
3. Atomic utlility classes 


### Margin

```css
.margin-auto: 0 auto; 
```

## Flexbox 

```css
.flex{ display: flex;}

.flex-r{ flex-direction: row; }

.flex-c{ flex-direction: column; }

.flex-rr{ flex-direction: row-reverse; }

.flex-cr{ flex-direction: column-reverse; }



// Justify-Content
.just-start{ justify-content: flex-start;}

.just-end { justify-content: flex-end;}

// Align -items 
.align-start { align-items: flex-start;}

.align-end { align-items: flex-end;}


// Flex-Wrap 
.flex-wrap { flex-wrap: wrap;}

```

## Position
```css
.relative { position: relative; }

.absolute { position: absolute;}

.fixed { position: fixed;}
```

## Text
```css
.txt-l{ text-align: left; }

.txt-r{ text-align: right;}

.txt-c{ text-align: center; }

.txt-dec-none { text-decoration: none; }
```

## Display
```css
.block{ display: block}; 

.block-in{ display: inline-block}; 

.none{ display: none}; 

.block{ display: block}; 



```

## SCSS color Variables 
```scss
$off-white: #F0FFFF; 

$white:#FFFFFF; 

$black:000000; 

$aqua: #00FFFF; 

$cyan:#00FFFF; 

$crimson:#DC143C; 

$dark-orange:#FF8C00; 

$deep-pink:#FF1493; 

$light-blue:#bfd7ff; 

$pale-green:#b5e0b1; 

$army-green:#699165;

$dark-red: #681a0a; 

$gold: #aa721e; 

```

### OverFlow 
```css
.overflow-h { overflow: hidden; }

.overflow-x-s { overflow-x: scroll; }

.overflow-y-s { overflow-y: scroll; }
```


### list
```css
.list-sn { list-style: none; }
```