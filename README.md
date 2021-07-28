# inventoryInUnity
setup an inventory fast in unity. Scripts included.

This inventory system will be composed visually by a box containing the image of the item, and arrows to travel through the inventory.
--------------
MANUAL
-------------

1. Add a new Empty to your scene named "Inventory"

2. Add a script component to Inventory.

3. Copy & Paste the code founded in the github to your script.

4. Add a button to your scene with 150x150 dimensions.
>We'll set basic widths, feel free to set as your desires.

5. Add a new event in the Button "On Click()".

6. Drag & Drop Inventory to the new fill created.

7. Add as function of Inventory */Inventory/ConsumeItem()*

>We'll now make de side buttons to switch selected item.

8. CTRL+D the Button, and set to the new one 70x70 as dimensions.

9. Do the same and put them on both sides of the ConsumeItem() button.

10. Stylize your buttons : add to the side buttons arrows as text/ image, or other...

11. Name the buttons respectively "GetPreviousItem" and "GetNextItem" and add them their OnClick() functions (GetPreviousItem() / GetNextItem() )

12. Delete UseItemButton's text, and add an Image instead.

13. Add the invisible pixel in the reference fill in Inventory script (in the repo).
>If you don't, you'll get a white square when there's no item selected, which is... yeah...

*We'll now make a text over/under the current item box that tells us the name of what we're holding.*

14. Right Click Canvas --) Add a new Text.

15. Customize your text and place it where you want it to be.

16. Last-step-finishing time for our inventory system ! You may now, before etablishing ScriptableObjects :
    - anchor all your objects (buttons and text) to where these are located : Anchor it to bottom left if your inventory stuff is located at the bottom left, top right for top-right-located UIs...

    - Add the missing references of your scripts.

-----------------------
Scriptable Objects :

1. Create a new script "Item" and open it.

2. Add the repo's code in it.

3. Return to Unity. To make your scriptable objects, the path is Assets/Create/Inventory/Item.
