twbs-contextual-modals
=====================

The Contextual Modals LESS mix-in for [Twitter Bootstrap 3](https://github.com/twbs/bootstrap) allow you to use the five contextual styles that you're used to having available for alerts, button, and labels to style your modals.
## Examples
In addition to the screenshots below, you can view the contextual modal styles by cloning this repository and opening <code>index.html</code> from the examples directory in your browser.

### Screenshots
The following images are screenshots of the actual modal styles from the examples file.

#### Default
![A modal using the .modal-default class](https://raw.github.com/binlabs/twbs-contextual-modals/master/examples/screenshots/modal-default.jpg)

#### Primary
![A modal using the .modal-primary class](https://raw.github.com/binlabs/twbs-contextual-modals/master/examples/screenshots/modal-primary.jpg)

#### Danger
![A modal using the .modal-danger class](https://raw.github.com/binlabs/twbs-contextual-modals/master/examples/screenshots/modal-danger.jpg)

#### Warning
![A modal using the .modal-warning class](https://raw.github.com/binlabs/twbs-contextual-modals/master/examples/screenshots/modal-warning.jpg)

#### Info
![A modal using the .modal-info class](https://raw.github.com/binlabs/twbs-contextual-modals/master/examples/screenshots/modal-info.jpg)

## Installation
There are two ways to install the contextual modal styles for Twitter Bootstrap 3. The first method uses the LESS mix-in, and the second simply uses the CSS file.

### LESS
Installing the Contextual Modal styles using the LESS mix-in makes it easier to customize to fit your theme's color scheme.

1. Download twbs-contextual-modals.
2. Move <code>bootstrap-contextual-modal.less</code> to your LESS directory.
3. Copy and paste the contents of <code>mixins.less</code> to your own <code>mixins.less</code> file.
4. Copy and paste the contents of <code>variables.less</code> to your own <code>variables.less</code> file, preferably near the existing lines of modal variables.
5. Compile your theme.
6. Initiate a modal using the <code>.modal</code> class and the class of the contextual style you want to use, such as <code>.modal-danger</code>.

### CSS
To install the contextual modal styles using just CSS, follow the instructions below.

1. Download twbs-contextual-modals.
2. Move <code>bootstrap-contextual-modal.css</code> to your CSS directory or copy the styles and paste them in to your theme's stylesheet.
3. Initiate a modal using the <code>.modal</code> class and the class of the contextual style you want to use, such as <code>.modal-danger</code>.
