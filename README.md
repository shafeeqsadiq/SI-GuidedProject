# Grocery Shopping List App

A Kotlin-based Android application that helps users manage their grocery shopping list with features to add, delete, and track items along with their quantities and prices.

## Features

1. **Item Management**
   - Add new grocery items with name, price, and quantity
   - Delete existing items with a single click
   - Real-time updates to the grocery list

2. **User Interface**
   - Clean and intuitive RecyclerView layout
   - Floating Action Button (FAB) for adding new items
   - Dialog-based item entry system
   - Toast notifications for user feedback

3. **Data Persistence**
   - Local database storage using Room
   - ViewModel architecture for data management
   - Repository pattern implementation

## Project Structure

The project follows MVVM (Model-View-ViewModel) architecture:
- **MainActivity**: Main UI controller
- **GroceryViewModel**: Manages UI-related data
- **GroceryRepository**: Handles data operations
- **GroceryDatabase**: Local database implementation
- **GroceryRVAdapter**: RecyclerView adapter for list display



