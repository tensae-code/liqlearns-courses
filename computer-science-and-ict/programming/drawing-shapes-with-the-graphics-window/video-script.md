# Video script — Drawing Shapes with the Graphics Window

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The GraphicsWindow draws by named operations. **DrawLine** rules a line between two points. **DrawRectangle** draws a rectangle from its corner, width and height. **DrawTriangle** joins three given points. **DrawEllipse** draws the ellipse inside a given rectangle's frame. Each operation takes the shape's coordinates as its arguments — the previous lesson's grid at work: a drawing program is a list of shapes, each named, each placed by numbers.
Beside every Draw stands its **Fill** partner — FillRectangle, FillEllipse and the rest — which paints the shape's inside solid. Two settings dress all drawing: **PenColor** and **PenWidth** rule the outlines (their colour and thickness), and **BrushColor** rules the fills. Set them before the operation they should dress; the window remembers them until changed. Mongolia's drawing discipline follows: plan the picture as shapes, set pen and brush, draw outlines, fill insides — the order a draughtsman works, written as a program.
