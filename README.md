# Markdown 
---
# Learning Markdown for technical communications

## Overview 

## Session Outline
![Markdown class](/Markdown_class.jpg)


## Introduction
Markdown is a light-weight markup language with plain-text formatting syntax for technical writing. The original creator of Markdown, John Gruber defines it as follows:
“Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML).”

Markdown utilization aspect to technical documentation is currently explained in the document for a better understanding.
Markdown basic syntax required for technical documentation is currently explained in the document for a better understanding. The basic syntax outlined by John Gruber are supported by nearly all the Markdown application editors.

## Testing GitHub flavour

Your computer crashed? Try sending a
<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd>


Strikethrough: ~~It was created by John Gruber in 2004.~~
~~Serena

## Nested table

    
<table class="table table-striped">
<caption>Caption for this Table</caption>
<thead class="thead-dark">
<tr>
<th width="30%">Property</th>
<th width="70%">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>Topic1</td>
<td>Topic2
<ul>
<li>Bullet item</li>
<li>Bullet item</li>
</ul>
</td>
</tr>
<tr>
<td>TopicA</td>
<td>TopicB</td>
</tr>
</tbody>
</table>


## Relation between Markdown and Markup 
Markdown belongs to the family of Markup languages. Introduced as a plain text, Markdown has short codes which are simple to remember unlike tags and formatting rules used in Markup languages.  

# Significance of Markdown Syntax
Markdown is beneficial in terms of its portablity, platform independency, and multipurposeful utility. 

It can be saved in various applications as follows:

Name | File Extension saved as |
---|-----------|
GitHub | .md|
API | .md|
   
# Markdown Syntax and Flavours

## Markdown Syntax
The syntax used in Markdown can be classified into two parts as follows:
* Basic Syntax
* Advanced Syntax

In general, a combination of syntax is used by specific applications designed to support writing in Markdown.

### Basic Syntax of Markdown
The basic syntax used in Markdown are in Perl script. Although there are some minor variations and improvisations, the basic codes remain the same for the following:
* Headings
* Paragraphs
* Emphasis
* Blockquote
* Images
* Code Blocks
* Links
* Tables
* Hyperlinks

The basic syntax composes of the following:
* Short codes:
   * Short code symbols - # , ` , *, - , etc.
   * Tabs
   * Spaces. 

* Blocks
  
# Blocks used in Markdown Syntax
Blocks consist of structural elements such as paragraphs, blockquotations, lists, headings, rules, and code blocks.
Some blocks consist of other blocks (leaf blocks) while some contain inline content.

* Blocks in MD are classified into the following:
   * ***Leaf Blocks*** - contain other blocks 
   * ***Container Blocks*** - do not contain other blocks.

## Leaf Blocks
Leaf Blocks are of five types as follows:
* ATX Heading
* SeText Heading
* Thematic breaks
* Code blocks
* HTML Elements

Example for Leaf block for heading level one is given below. 
### Heading Level one
Headings are used for generally used for inline content, image, table, references. For creating a heading, add hash symbol (#) in front of a word or phrase intended to be written as a heading.
The number of hash symbols added in front of word or phrase, intended to be written as heading, will correspond to the heading level. For example, to create a heading level two, use two number signs (e.g., ## Header two).

Heading number | Code in MD |
--------|-------|
*Heading 2* | ## Heading 2 |

## Container blocks
Container blocks include the following:
* Block quotes
* Lists
* List items
* Tables


### Output of Markdown Syntax
The [WYSIWIG editors](https://techwriterstribe.com/) show formatting upfront. Markdown source file created shows the syntax elements with the file. The formatted content only is displayed in the output. The output is generally is in the form of HTML, however PDF output also has become dominant in recent days.  

## Markdown Flavours
The Markdown Flavours include the variants created by the combination of syntax used by a particular Markdown supporting application.

# Markdown Editors
Using Markdown Editors, a Markdown document can be written easily and be exported to HTML or PDF directly. 

Operating System | Name of OS-specific MD Editor |
---|------------|
*Mac* | MacDown, iA Writer or Marked |
iOS / Android | iA Writer |
*Windows* | ReText or ghostwriter |
*Web* | Dillinger or StackEdit |

 
# Process flow of MD Application
The process flow of MD application includes the following steps:
1.  *MD Files* are saved with extension .md or .markdown.
2. *MD Application* processes the MD file with processor.
3. *MD Processor*, also known as Parser or Implementor, converts MD files to HTML output or other desired output types.
4. *Output* is exported through HTML or PDF format.




