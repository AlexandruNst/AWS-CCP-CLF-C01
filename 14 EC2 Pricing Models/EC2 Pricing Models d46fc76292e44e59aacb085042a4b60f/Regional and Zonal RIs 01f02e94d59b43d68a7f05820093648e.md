# Regional and Zonal RIs

When you purchase an RI, you determine the **scope**

**Does not affect the price, but the flexibility of the RI**

| Regional RI | Zonal RI |
| --- | --- |
| Purchased for a Region | Purchased for an AZ |
| Does not reserve capacity
If AWS runs out of servers, you’re not gonna have them | Reserves capacity in the AZ
Guaranteed to be there when you need them |
| RI discount applies to any AZ in the Region | RI discount applies only in the selected AZ |
| RI discount applies to instance of the same family, regardless of size (Only on Amazon Linux with default tenancy) | No instance size flexibility. RI discount applies for the exact family and size |
| You can queue purchases for Regional RI | Cannot queue purchases for zonal RI |