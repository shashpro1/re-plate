# RE-PLATE AI

### Every Meal Deserves a Destination.

FoodRescue AI is a project developed by Team KR ALPHA to help reduce food waste by connecting restaurants, college canteens, and event organizers with organizations that can distribute surplus food to people in need.

Sometimes, good food goes unused because there is no proper way to find recipients or arrange collection on time. Our idea is to make this process easier through a platform where food providers can share available food and recipients can find and reserve what they need.

## What We Are Building

**1. AI Rescue Autopilot**
Helps identify suitable recipients based on their needs, available capacity, location, and collection time.

**2. Live Donation Network**
Allows food providers to post surplus food and recipients to reserve the quantity they need.

**3. Rescue Chain Reaction**
If a pickup is cancelled, the system looks for another possible recipient so that the remaining food has another chance of being collected.

**4. Surplus Prevention Advisor**
Uses previous donation records to help providers understand their food surplus and plan future preparation better.

## How It Works

1. A restaurant or canteen adds details about its surplus food.
2. The system finds suitable recipient organizations.
3. Recipients can reserve the available quantity.
4. The provider and recipient coordinate the pickup.
5. If a pickup fails, the system checks whether another recipient can collect the food in time.
6. Previous records help providers understand and manage surplus.

## Technologies We Plan to Use

* React and TypeScript for the frontend
* Firebase Authentication for login
* Cloud Firestore for storing donation and reservation details
* Firebase Cloud Functions for important backend operations
* Rule-based matching initially, with AI features added where useful

## Our First Prototype

We plan to demonstrate the idea using a simple example:

A provider lists 80 portions of food. One recipient reserves 30 portions, leaving 50 portions available. If a pickup is cancelled, the system checks whether another recipient can collect the remaining food and suggests an alternative when possible.

This will help us demonstrate how the platform handles donations, reservations, and failed pickups.

## Why This Project Matters

We want to make food donation easier to manage and reduce the amount of suitable surplus food that goes uncollected. Our focus is not just on listing available food, but also on helping coordinate its collection.

Food safety and proper handling will remain important throughout the process.

## Team KR ALPHA

* SOORYAPPRAKHASH E
* AKSHAY KUMAR R
* SHAHITH S
* SRI KAVIBHARATHI K

## Current Status

We are currently working on the initial setup and prototype. Features will be added and tested step by step as development progresses.

**Our goal:** Make food rescue simpler, faster, and more organized.

*Every Meal Deserves a Destination.*
