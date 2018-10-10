<template>
  <div>
  <h1>Coding Challenge: ta.co builder</h1>
    <h2>Details</h2>
    <ul>
      <li>We will build an app to let users design a taco.</li>
      <li>Each ingredient has a cost associated with it.</li>
    </ul>
    <h2>Business Requirements</h2>
    <ul>
      <li>User is required to select a shell (hard or soft)</li>
      <li>User is required to select a single protein (chicken, beef, pork)</li>
      <li>User can optionally select an unlimited number of toppings.</li>
      <li>User can see the prices of each ingredient.</li>
      <li>User can see a live running tally of their taco cost.</li>
      <li>
        User should not be able to order until all required choises are made.
      </li>
    </ul>
    <h2>Implementation Details</h2>
    <ul>
      <li>Construct a payload to submit when the user clicks order.</li>
      <li>Reset the form after the user clicks the order button.</li>
    </ul>
    <p>
      <strong>Note:</strong>
      <span>You only need to construct the payload, no ajax required!</span>
    </p>
    <h3>Example Payload</h3>
    <code>
      {
        '{shell: "hard", protein: "chicken", toppings: ["tomato", "onion", "cheese"]}'
      }
    </code>
    <h3>Ingredient Costs</h3>
    <table>
      <tbody>
        <tr>
          <th colspan="2">Shells</th>
        </tr>
        <tr>
          <td>Soft</td>
          <td>$0.25</td>
        </tr>
        <tr>
          <td>Hard</td>
          <td>$0.10</td>
        </tr>
        <tr>
          <th colspan="2">Protein</th>
        </tr>
        <tr>
          <td>Chicken</td>
          <td>$1.25</td>
        </tr>
        <tr>
          <td>Beef</td>
          <td>$1.00</td>
        </tr>
        <tr>
          <td>Pork</td>
          <td>$2.25</td>
        </tr>
        <tr>
          <th colspan="2">Toppings</th>
        </tr>
        <tr>
          <td>Tomato</td>
          <td>$0.15</td>
        </tr>
        <tr>
          <td>Cheese</td>
          <td>$1.00</td>
        </tr>
        <tr>
          <td>Lettuce</td>
          <td>$0.10</td>
        </tr>
        <tr>
          <td>Onion</td>
          <td>$0.20</td>
        </tr>
        <tr>
          <td>Sour Cream</td>
          <td>$0.75</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
  export default {
    name: 'Exercise',
    props: {}
  }
</script>
