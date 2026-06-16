# Session 2a - Total Cost of Ownership (TCO) Analysis

## Lab Objective

The objective of this activity was to apply the Total Cost of Ownership (TCO) methodology by comparing a cloud-based infrastructure solution with a traditional on-premises infrastructure solution. Fixed and variable costs were analyzed to determine the overall cost of ownership and identify the most cost-effective deployment option over a three-year period.

---

## Deliverable 1 – Infrastructure Models Chosen

| Option                              | Type                       | Intended Use                 |
| ----------------------------------- | -------------------------- | ---------------------------- |
| Microsoft Azure B2s Virtual Machine | Cloud Infrastructure       | Small Business / Web Hosting |
| Dell PowerEdge T150 Server          | On-Premises Infrastructure | Small Office / Local Hosting |

The Azure B2s Virtual Machine is a cloud-based solution that rents computing resources on demand. The Dell PowerEdge T150 represents a traditional server that requires ownership of hardware, software licenses, and ongoing maintenance.

---

## Deliverable 2 – Cost Assumptions

The following assumptions were used throughout the analysis:

| Assumption               | Value                           |
| ------------------------ | ------------------------------- |
| Analysis Period          | 3 Years                         |
| Server Runtime           | 24 Hours per Day                |
| Operating Days           | 365 Days per Year               |
| Azure VM Type            | B2s (2 vCPU, 4GB RAM)           |
| Storage Requirement      | 64GB SSD                        |
| Electricity Rate         | S$ 0.30/kWh                     |
| Server Power Consumption | 200W Average                    |
| Software Requirement     | Windows Server 2022 Standard (16-core) |

These assumptions were used consistently across all cost calculations.

---

## Deliverable 3 – List of Expense Items

### Cloud Infrastructure Costs

#### Fixed Costs

- Initial deployment and configuration

#### Variable Costs

- Monthly virtual machine charges
- Storage charges
- Public IP charges
- Backup service charges

### On-Premises Infrastructure Costs

#### Fixed Costs

- Physical server hardware
- Windows Server license
- UPS power backup

#### Variable Costs

- Electricity consumption
- Hardware maintenance
- Replacement components


---

## Deliverable 4 – Unit Costs Sourced

| Item                       | Cost | Unit         | Source                                                                            |
| -------------------------- | ---- | ------------ | --------------------------------------------------------------------------------- |
| Azure B2s VM               | S$ 44.38   | per month    | Azure Pricing Calculator                                                          |
| Azure Managed Disk 64GB    | S$ 10.21   | per month    | Azure Pricing Calculator                                                          |
| Azure Public IP            | S$ 2    | per month    | Azure Pricing Calculator                                                          |
| Azure Backup Service       | S$ 5    | per month   | [Azure Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/) |
| Dell PowerEdge T150 Server | S$ 2800 | one-time | [Sim Lim](http://www.simlimsquare.com.sg/public/product/dell-poweredge-t150-poweredge-t150-xeon-e-2324g-1x8gb-di-9847)                                      |
| Windows Server 2022 Standard     | S$ 1173 | SGD one-time | [SourceIT](https://sourceit.com.sg/products/dell-microsoft-windows-server-2022-standard-rok-16-core-634-bykr?srsltid=AfmBOoq-IAjBhyEDJPdYlU8TxIgrl5_OG_VOotR4om9mxrUrdpna7Q4R&utm_source=chatgpt.com)                       |
| UPS Backup Unit            | S$ 200  | one-time | Retail estimate                                                                   |
| Electricity                | S$ 0.3  | per kWh      | [SP Group Singapore](https://www.ema.gov.sg/consumer-information/electricity/buying-electricity/buying-at-regulated-tariff)                                 |
| Maintenance                | S$ 150  | per year     | Assumption                                                                        |

The pricing information was obtained from the Azure Pricing Calculator, Dell Singapore, Microsoft Licensing information, and SP Group Singapore.

---

## Deliverable 5 – TCO Calculation

| Cloud Cost Item  | Type     | Unit Price | Units (months) | Total Cost |
| ---------------- | -------- | ---------- | -------------- | ---------- |
| Azure B2s VM     | Variable | 44.38      | 36.00          | 1,597.68   |
| Storage          | Variable | 10.21      | 36.00          | 367.56     |
| Public IP        | Variable | 2.00       | 36.00          | 72.00      |
| Backup           | Variable | 5.00       | 36.00          | 180.00     |
| Cloud 3-Year TCO |          |            |                | 2,217.24   |


| On-Prem Cost Item            | Type     | Unit Price | Units    | Total Cost |
| ---------------------------- | -------- | ---------- | -------- | ---------- |
| Dell Server                  | Fixed    | 2,800.00   | 1.00     | 2,800.00   |
| Windows Server 2022 Standard | Fixed    | 1,173.00   | 1.00     | 1,173.00   |
| UPS                          | Fixed    | 200.00     | 1.00     | 200.00     |
| Electricity                  | Variable | 0.30       | 5,256.00 | 1,576.80   |
| Maintenance                  | Variable | 150.00     | 3.00     | 450.00     |
| On-Prem 3-Year TCO           |          |            |          | 6,199.80   |


---

## Deliverable 6 – Monthly and Yearly Cost Comparison

| Period      | Cloud Cost | On-Premises Cost |
| ----------- | ---------- | ---------------- |
| Monthly     | 61.59      | 172.22           |
| Yearly      | 739.08     | 2,066.64         |
| Three Years | 2,217.24   | 6,199.80         |

The cloud solution remained less expensive throughout the analysis period.

---

## Deliverable 7 – Break-even Analysis

| Year   | Cloud Cumulative | On-Prem Cumulative |
| ------ | ---------------- | ------------------ |
| Year 1 | 739.08           | 2,066.64           |
| Year 2 | 1,478.16         | 4,133.28           |
| Year 3 | 2,217.24         | 6,199.92           |

### Break-even Analysis

No break-even point occurred during the three-year period because the cloud solution remained cheaper than the on-premises solution at every stage of the comparison.

---

## Deliverable 8 – Reflection Questions

### Which option has the lower TCO and why?

The Microsoft Azure B2s Virtual Machine has a lower Total Cost of Ownership because there is no requirement to purchase physical hardware, software licenses, or UPS equipment. Maintenance responsibilities are also transferred to the cloud provider.

### Would the choice change for a larger organization?

Possibly. Large organizations with stable workloads may find that purchasing infrastructure becomes more economical over a much longer period. However, this depends on growth, hardware refresh cycles, and operational requirements.

### What other factors should be considered?

- Scalability
- Reliability
- Security
- Vendor support
- Disaster recovery
- Backup capabilities
- Compliance requirements

### What is important for enterprise infrastructure?

- High availability
- Redundancy
- Security controls
- Performance
- Storage capacity
- Disaster recovery planning

### What is the estimated break-even point?

No break-even point occurred within the 3-year analysis period.

---

## Lab Summary

The analysis showed that the cloud infrastructure provides greater flexibility and lower upfront costs, making it a cost-effective option for small and medium-sized organizations. Over the three years, the Microsoft Azure B2s Virtual Machine had a lower Total Cost of Ownership than the on-premises Dell PowerEdge T150 server.

