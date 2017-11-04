# ooo-maker

Given a GitHub username and a month/date string, this will take your GitHub avatar and slather the
words `OOO 'til <month/date>`.

In other words, from this:

![current](https://user-images.githubusercontent.com/64050/32126072-b90cdaec-bb23-11e7-8e24-c74d36036ca8.jpeg)

to this:

![branded](https://user-images.githubusercontent.com/64050/32126068-b693da68-bb23-11e7-977d-87db4c7600f5.png)

## Installation

**You will need [the dependencies outlined in `node-canvas`](https://github.com/Automattic/node-canvas#installation)** before using this tool.

Once that's done, run:

    npm install -g ooo-maker

> Requires `node` to be available in your PATH. If you're using a system where
> the node binary is named `nodejs` instead, you'll need to symlink it or something.

## Why?

I got tired of doing this myself.

## Usage

    ooo-maker -u <GitHub_username> -d <month/date>
