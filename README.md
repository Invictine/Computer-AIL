# Invictine Hotels

A school web-design project for a fictional hotel group in Shimla, with a room catalog, facilities gallery, and pricing microsite.

## Tour the site

Open [Homepage.html](AIL%20Website/Homepage.html) from a local copy to explore the properties, facilities, and eight room types. Use the room-pricing link to open [introPage.html](AIL%20Website/introPage.html), which includes the pricing cards and an introductory video.

The booking button opens a demo state. The project is built with HTML, CSS, and JavaScript and runs without a build step.
## Tour the pricing video

<video src="AIL%20Website/0001-1345.mp4" controls width="100%" aria-label="Invictine Hotels project video"></video>

## Page structure

```mermaid
flowchart LR
  Home[Homepage.html] --> Rooms[Eight room pages]
  Home --> Facilities[Facilities gallery]
  Home --> Pricing[introPage.html and pricing cards]
```

The pages are static HTML, CSS, and JavaScript examples; the booking action is a demo state and there is no hotel reservation backend.