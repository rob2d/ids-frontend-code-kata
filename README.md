# Message Dialog Kata

## Introduction

A Kata is a Japanese word meaning “form”, and in the martial arts it describes a choreographed pattern of movements used to train yourself to the level of muscle memory. We use this Kata to check your form and style while creating a Javascript Web Component.

For this Kata, imagine our Design team would like you to create a simple error dialog called a message dialog `<custom-message-dialog>`.

This message dialog should appear in the middle of the page when clicking on the `<custom-button>` that reads *Show Error Message*.  The Message dialog should try to follow the design standards and technology standards we set out.

## Working Example

This is an example of a legacy jQuery-based component we use in production.  The ultimate goal would be to replicate something similar to this example as a Web Component: [Message Dialog Example](https://main-enterprise.demo.design.infor.com/components/message/example-error.html?layout=nofrills)

## Goal

Your goal is to write the necessary HTML, CSS and JavaScript to replicate this legacy component.  The Infor Design System (IDS) is moving towards a WebComponent-based system. We would like you port the basic functionality of this Message Dialog into a web component, using a custom element as its base. 

The Webcomponent specification is explained in detail at [MDM](https://developer.mozilla.org/en-US/docs/Web/Web_Components)

The `<custom-message-dialog>` component appear when clicking on the `<custom-button>`.

Once the message is displayed, we'd also like you to offer an option to hide it. Functionally, this can occur two ways:

1. Hitting `ESC` on your keyboard
1. Clicking on the button in the message dialog

When styling the web component take a look at this, these articles can provide you with some ideas for technique: 

- [css tricks article](https://css-tricks.com/styling-a-web-component/) 
- [constructable style sheets](https://developers.google.com/web/updates/2019/02/constructable-stylesheets).

## Requirements

1. Runs in Chrome only by opening the index.html page
1. Try not using any external dependencies or libraries (in our production projects this is a requirement, excluding test dependencies)
1. The old example uses jQuery, since we are using web components now jQuery should not be used in your Kata
1. Style it to be as close to the old example as possible. (This project provides the svg icon in the `./images` folder)

## What We Are looking For

1. Understanding of how to construct a Custom Element from scratch
1. Understanding of the WebComponent lifecycle [as described on MDN](https://developer.mozilla.org/en-US/docs/Web/Web_Components)
1. Attention to detail
1. Code Style in HTML, Css and JS
1. Decisions about minumum viable product, and what might be provided later as enhancements (for example: Accessibility Considerations / Testing)

## Delivery Method

Fork this repo and do a pull request with your working code.
