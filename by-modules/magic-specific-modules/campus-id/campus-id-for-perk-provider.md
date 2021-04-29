# Campus ID for Perk Provider

### Create Perk

### Manage Redeem Requests

### Secret Message

### Redemption Request Workflow

<table>
  <thead>
    <tr>
      <th style="text-align:left">Status</th>
      <th style="text-align:left">Trigger By</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Submitted</b>
      </td>
      <td style="text-align:left">Redeemer</td>
      <td style="text-align:left">
        <ul>
          <li>RP is minus from the Redeemer account and store temporarily at ESCROW.</li>
          <li>Redemption request is displayed on the Provider interface to process.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Processing</b>
      </td>
      <td style="text-align:left">Provider</td>
      <td style="text-align:left">
        <ul>
          <li>To mark the request is under process by the Provider.</li>
          <li>Can proceed next to either <code>Rejected</code> or <code>Approved</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Rejected</b>
      </td>
      <td style="text-align:left">Provider</td>
      <td style="text-align:left">
        <ul>
          <li>To reject the redemption request</li>
          <li>RP is returned to the Redeemer account from ESCROW</li>
          <li>Rejected request can be revived by revert it to <code>Processing</code> status.
            RP will be minus from the Redeemer account again and store temporarily
            at ESCROW.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Approved</b>
      </td>
      <td style="text-align:left">Provider</td>
      <td style="text-align:left">
        <ul>
          <li>Provider accepted this redemption and is preparing for its delivery.</li>
          <li>Secret message will be pre set in note to redeemer and sent thru email.
            Secret message normally carries instruction on how to acquire the products
            or services, like a voucher code for example.</li>
          <li>The redeemer can proceed next to <code>Delivered</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">Provider</td>
      <td style="text-align:left">
        <ul>
          <li>This marks the end of workflow on the Provider side.</li>
          <li>RP will be transferred to the Provider account.</li>
          <li>For physical products or services, it means the parcel had been sent to
            courier services. Delivery tracking code can be inserted in the Note to
            Redeemer.</li>
          <li>For digital products or services, instruction to acquire had been sent
            in the <code>approved</code> stage thru secret message.</li>
          <li>This action is not revertable.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Completed</b>
      </td>
      <td style="text-align:left">Redeemer</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>

{% hint style="info" %}
This feature is currently under development. Please come back later.
{% endhint %}

