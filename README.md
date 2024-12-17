<!--
- https://github.com/skydev-x/corne-zmk-5-column?tab=readme-ov-file
- https://github.com/wolfwood/glove80-zmk/tree/main
- https://github.com/minusfive/zmk-config
- https://nickcoutsos.github.io/keymap-editor/

GRAVE and TILDE work fine for Mac U.S. default physical keyboard, but for Swiss french keyboard with US software layout they yield § and ±. British English needs to be activated to correctly yield GRAVE in layer 2 but TILDE still doesn't produce ~, but ¬.

TO DO:
- Use shift + numbers to yield ()!@#$%: Mejor no porque significaria cambiar de layer + shift + number position
    - shift + number position = ()!@#$%????
    - opt + N = ˜˜˜˜˜˜˜ 
- MIDNIGHTS MODE (RGB)
- design RGB modes with TS album names
-->

# Corne ZMK 5-column keyboard
## Anti-Typing layout

Switching from a staggered to a corne keyboard can be challenging, as it initially feels unnatural. Additionally, a 5-column layout can sometimes limit the ability to assign extra functionality or make layers more efficient. The purpose of the **Anti-Typing layout** is to embrace a more personalized, innovative design that empowers users. It keeps the 5-column Corne's simpler, minimalist structure while making it more similar to the traditional QWERTY keyboard, thus reducing the learning curve. For example, to type a colon (":") in the 5-column layout, you would typically need to switch to another layer and press the key assigned to the colon. However, in this layout, in the default layer you simply press `SHIFT` + `;` to produce a colon (":"), just as you would on a regular laptop keyboard.

<!--
the stories of 13 sleepless nights ...
late-night coding sessions
-->

The name is inspired by Taylor Swift's 10th album *Midnights* and my sleepless nights spent building this layout, during which the album kept me company, with Anti-Hero playing on an endless loop.

### Layout philosophy
> [!NOTE]
> This is a work in progress.

- Focused on simplicity, and minimalistic in its core.
- Prioritize ergonomics while reducing the learning curve.
- Reduce the finger movement and layer switching.

## Layers
> [!NOTE] 
> If you see more than one symbol in the same key, it means that it can be activated in the same layer by pressing ⌘, ⌥, ⌃, ⇧ as you would normally do it in Mac, or SHIFT, CONTROL and ALT in Windows.

![Default layer](images/default_layer.png)

![Lower layer](images/lower_layer.png)

![Raise layer](images/raise_layer.png)

> [!IMPORTANT]  
> The symbols \` and ~ on a Mac US keyboard yield § and ±, respectively. To correctly generate ` on raise layer, British English must be activated. However, ~ still does not produce ~ and instead generates ¬.
