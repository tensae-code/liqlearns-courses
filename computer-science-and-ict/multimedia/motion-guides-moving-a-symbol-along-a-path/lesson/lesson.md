# Motion guides — moving a symbol along a path

## Do it first

Draw a circle on paper. Put a coin at the top of the circle and slide it slowly all the way round back to the start. Before reading on, say what stayed fixed and what moved. In Flash, the circle is drawn once on its own layer — and the symbol does the travelling.

## Motion along a path — the book's full order

A motion effect sends an object along a drawn path using a **guide layer**, in the book's full order:

1. Place a graphic symbol on the stage and name its layer **Graphic**.
2. **Right-click the layer label → Add Motion Guide** — a guide layer appears above, marked with the guide icon.
3. **Draw the path** in the guide layer — a circle is the example.
4. Select **frame 60** of the guide layer and press **F5** to insert frames.
5. On **frame 1** of the Graphic layer, drag the symbol to **one end** of the path, with its **bubble right below the path**.
6. On **frame 60** press **F6** for a new keyframe and drag the symbol to the path's **other end**, bubble again below the path.
7. **Right-click any frame between 1 and 60 → Create Motion Tween**.
8. **Ctrl+Enter** to view the result.

[Picture 15313 — a symbol on its guide path]

[GIF 15324 — the symbol travelling around the drawn circle]

Every step earns its place: no guide layer, no path; no end keyframes, nowhere for the tween to travel between; no bubble under the path, and the symbol does not lock onto the route.

## Say it to your companion

Recite the eight steps to your companion in order, naming every key press (F5, F6, Ctrl+Enter) where it belongs. Your companion checks against the lesson.

## Do It Yourself

1. Write the eight steps in order from memory; mark the three key presses.
2. Why must the bubble sit right below the path at both ends?
3. What does the tween actually do between frame 1 and frame 60?
