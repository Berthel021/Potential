# Business Fee Calculator

A dynamic fee calculator for businesses of different sizes with configurable options for various services.

## Features

- **Business Size Categories**: Calculates fees based on 7 revenue tiers
- **Service Configurations**: 5 customizable options that affect pricing
- **Youth Employment Calculation**: Computes costs based on number of youth employees
- **Dynamic UI**: Interface adapts based on selections
- **Detailed Breakdown**: Shows registration fees and per-youth costs

## Customizable Features

1. **B-BBEE Compliance Status** (`b-bbee-switch`)
   - Toggle that affects pricing for B-BBEE compliant vs non-compliant businesses

2. **Hosting Services** (`hosting`)
   - Option that enables/disables hosting services and affects pricing

3. **Source Services** (`source`)
   - Configurable source services option with pricing impact

4. **Phone Services** (`phones`)
   - Toggle for phone services availability

5. **Youth Employment** (`youth`)
   - Input field for number of youth employees that affects total costs

## Dependencies

This calculator requires:

- **jQuery 3.0+** (tested with 3.6.0)
  ```html
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
