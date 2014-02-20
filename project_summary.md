# Markdown testing

## Alex Coady (@alexcoady)

## Underscore copy that should not be italic
this_text_should_not_be_italic

## Auto marking up links
This link should get parsed all nice: http://example.com

## Strikethrough text
~~Strike out~~

## Fenced code blocks

```
function test() {
  console.log("notice the blank line before this function?");
}
```

## PHP fenced code

```php
function test() {
  print_r('testing testing');
}
```

## Tables

### Default

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

### With outer pipes

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

### Scruffy syntax

| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |

### Scruffy syntax with italics/strikethroughs etc

| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |

### Aligned text

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |