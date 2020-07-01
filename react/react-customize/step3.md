Next modify the cards.

1) <strong>Add a hover effect to the `card` component.</strong>

PatternFly components, including `card`, can be customized with properties. Add a hover effect to the cards with the `isHoverable` property.

It should look like this:

<pre class="file" data-target="clipboard">
&lt;Card isHoverable&gt;
</pre>

2) <strong>Make the card selectable.</strong>

Locate the `Card` component and add a new property `isSelectable` to allow selection of individual cards.

The opening tag for the Card component should now look like the following:

<pre class="file" data-target="clipboard">
&lt;Card isHoverable isSelectable&gt;
</pre>

Once the preview reloads, the page should look like this when hovering over a card:

<img src="react-customize/assets/step3.png" alt="Page demo with cards and hover effect" style="box-shadow: rgba(3, 3, 3, 0.2) 0px 1.25px 2.5px 0px;" />
