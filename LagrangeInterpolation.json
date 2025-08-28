{
  "program": {
    "language": "Java",
    "class": "LagrangeInterpolation",
    "methods": [
      {
        "name": "convertFromBase",
        "description": "Converts a number from a given base to decimal",
        "input": ["String value", "int base"],
        "output": "BigInteger",
        "steps": [
          "Define digits string (0-9, a-z)",
          "Initialize result = 0",
          "For each character in input value:",
          " - Validate digit against base",
          " - Update result = result * base + digit value",
          "Return result"
        ]
      },
      {
        "name": "lagrangeCoefficients",
        "description": "Computes coefficients of polynomial using Lagrange interpolation",
        "input": ["int[] xPoints", "BigInteger[] yPoints"],
        "output": "BigDecimal[] coefficients",
        "steps": [
          "Initialize coefficients array with zeros",
          "Loop over each data point i:",
          " - Initialize basis polynomial Li(x) as [1]",
          " - Initialize denominator = 1",
          " - Loop over j != i:",
          "    * Multiply polynomial by (x - xj)",
          "    * Update denominator *= (xi - xj)",
          " - Scale Li(x) by yi / denominator",
          " - Add contribution to coefficients",
          "Return coefficients"
        ]
      },
      {
        "name": "main",
        "description": "Runs base conversion and Lagrange interpolation with predefined data",
        "input": "None",
        "output": "Console output",
        "steps": [
          "Define dataset with base and values",
          "Initialize xPoints and yPoints arrays",
          "Convert each value to decimal using convertFromBase()",
          "Store results in arrays",
          "Print conversion results",
          "Call lagrangeCoefficients() to compute polynomial coefficients",
          "Print coefficients",
          "Verify polynomial by evaluating at original x points and comparing with y values"
        ]
      }
    ],
    "data": {
      "points": {
        "1": { "base": 6, "value": "13444211440455345511" },
        "2": { "base": 15, "value": "aed7015a346d63" },
        "3": { "base": 15, "value": "6aeeb69631c227c" },
        "4": { "base": 16, "value": "e1b5e05623d881f" },
        "5": { "base": 8, "value": "316034514573652620673" },
        "6": { "base": 3, "value": "2122212201122002221120200210011020220200" },
        "7": { "base": 3, "value": "20120221122211000100210021102001201112121" },
        "8": { "base": 6, "value": "20220554335330240002224253" },
        "9": { "base": 12, "value": "45153788322a1255483" },
        "10": { "base": 7, "value": "1101613130313526312514143" }
      }
    }
  }
}
