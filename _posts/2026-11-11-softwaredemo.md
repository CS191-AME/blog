---
layout: post
title: "Software Demo"
---

# Hello

In this post, we demonstrate our progress on Halalan as of November 11, 2026. The prototype of our project requires working CRUDs for the Election, Position, and Party entities for a superadmin user.

## Election CRUD

<video controls width="100%">
    <source src="{{ '/assets/demo/election_CRUD.mp4' | relative_url }}"
            type="video/mp4">
    Your browser does not support HTML5 video.
</video>

Superadmins manage elections as shown above. Election nesting is illustrated by the indentation in the interface.

## Position CRUD

<video controls width="100%">
    <source src="{{ '/assets/demo/position_CRUD.mp4' | relative_url }}"
            type="video/mp4">
    Your browser does not support HTML5 video.
</video>

Positions can then be created, viewed, updated, and deleted after choosing an election from the drop-down menu.

## Party CRUD

<video controls width="100%">
    <source src="{{ '/assets/demo/party_CRUD.mp4' | relative_url }}"
            type="video/mp4">
    Your browser does not support HTML5 video.
</video>

Parties can be created, viewed, updated, and deleted in the same way.

## Election Running

<video controls width="100%">
    <source src="{{ '/assets/demo/election_RUNNING.mp4' | relative_url }}"
            type="video/mp4">
    Your browser does not support HTML5 video.
</video>

Clicking the status of an election toggles it between running and not running. A running election is indicated by a green status.

Also demonstrated is the inability to create new positions and parties while an election is running. This is not the final design; improvements such as a more obvious run button are planned.

## Election Not Running

<video controls width="100%">
    <source src="{{ '/assets/demo/election_NOT_RUNNING.mp4' | relative_url }}"
            type="video/mp4">
    Your browser does not support HTML5 video.
</video>

Clicking the status again turns the running election back into a not running one. The Show button under Results is now clickable to navigate to the results module that will be implemented later on.
