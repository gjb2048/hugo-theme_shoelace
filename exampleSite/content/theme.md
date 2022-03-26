---
title: Theme
description: Theme things
tags: ["go", "golang", "hugo"]
---

## Images

![Theme thumbnail](/images/tn.png "Thumbnail")

## Highlighting
{{< highlight java >}}
public class TestOne {
    private String name = "Java program";

    public static void main (String args[]) {
        TestOne us = new TestOne();
        System.out.println(us.getName());
    }

    public String getName() {
        return name;
    }
}
{{< / highlight >}}

This is a small Java program that I created.

## Bootstrap

When the parameter 'fullbs' is set to 'false', then only a subset of the CSS is served which has been created from the source to contain what is used in the theme.  If you want the all of Bootstrap with its JavaScript, then set this to 'true'.
