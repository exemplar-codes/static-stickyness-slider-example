# static-stickyness-sllder-example
Example of cascading stickyness of HTML elements, demonstrated using a slider

[See live emo](https://exemplar-codes.github.io/static-stickyness-sllder-example/)

<h2>Problems fixed</h2>
      <ol>
        <li>Slider footer respects long slider content.</li>
        <li>
          Slider header collapse - Scrolling long slider content collapses
          slider header.
        </li>
      </ol>
      <h4>
        Key insight: Preserve static flow by using flex instead of
        position-fixed, hacked with overflow-hidden
      </h4>
