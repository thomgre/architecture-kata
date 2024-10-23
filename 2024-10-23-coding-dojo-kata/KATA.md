# Architecture Kata: FreshShop

## Background

FreshShop, a growing retail chain with 400 stores across the world, is struggling with their current monolithic order management system. 
As they expand their e-commerce presence and add more fulfillment options, they need a new distributed system to handle orders across both online and physical stores.

## Current Situation

- Single monolithic system handling all orders
- 400 retail stores worldwide
- 8 distribution centers
- 1 e-commerce website
- Orders per day: 300,000
- Peak holiday orders: 600,000/day
- Current system frequently crashes during peak times

## Business Requirements

1. **Order Processing**
    - Handle orders from both stores and website
    - Support ship-to-home and in-store pickup
    - Process returns from any store
    - Real-time order status updates
2. **Inventory Management**
    - Track inventory across stores and warehouses
    - Update stock levels in real-time
    - Reserve inventory when orders are placed
3. **Business Intelligence**
	- (Near) real-time business analytics
	- Custom querying and dashboarding for business insights

## Technical Constraints

- Must integrate with existing point-of-sale (POS) systems in stores
- Order processing time must be under 3 seconds
- System must handle holiday shopping peaks
- 99.9% availability required
- Payment processing must be PCI compliant

## Challenge

Design a distributed order management system that:

1. Handles both online and in-store orders
2. Maintains accurate inventory across all locations
3. Scales for (holiday) shopping peaks
4. Provides consistent customer experience
5. Provides the business insights into operations


