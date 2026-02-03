## Overview
FunkoLens is an Angular-based Progressive Web App (PWA) that enables users to analyze recent completed eBay marketplace sales of Funko collectibles and manage a personal collection based on real transaction data.

The application allows authenticated users to search for specific items, review recent sales, and view pricing statistics such as averages, medians, and trimmed means. Based on configurable costs and fees, FunkoLens provides realistic profit and loss estimates for individual items as well ass aggregated value insights for an entire collection.

By focusing on completed sales rather than active listings, FunkoLens aims to deliver transparent, data-driven insights that support informed buying, selling and long-term value tracking decisions.

## Architecture Overview
FunkoLens follows a client-server architecture with an Angular-based PWA frontend and a backend service responsible for data retrieval, authentication, and persistence. External marketplace data is accessed exclusively through the backend to ensure security and data consistency.

## Key Features
- Search and analysis of completed eBay sales
- Pricing statistics (average, median, trimmed mean)
- Profit or loss estimation
- User accounts and personal collections
- Collection value tracking

## Tech Stack
- Frontend: Angular (PWA)
- Backend: API service
- Data source: eBay completed sales

> Note: This project is intended for private and educational purposes.
> All data is sourced from publicly available marketplace information.
