# Adventure Starter

## Running the code

1. Type node game.js to run the project
2. Type npm install to install the tests
3. Type npm test to run the tests

## Tasks

Your task is to add different items to this simple adventure world.

1. Fill out the `Item` class in __item.js__
2. Implement instance methods to pick up and drop items
    `room.getItemByName` - Retrieves an item from a room by name
    `player.getItemByName` - Retrieves an item from a player's inventory by name
    `player.takeItem` - Picks up an item from a room into the player's inventory
    `player.dropItem` - Drops an item the player is holding into their current room
3. Create an edible `Food` class that inherits from `Item`
4. Modify the `loadWorld` function in __world.js__ to create food from __world-data.js__
5. Implement `player.eatItem` to allow the player to eat food items, but not non-food items
6. Bonus: Add new types of enemies, items and rooms
