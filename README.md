# Jukebox Bot System

## Commands

### Note:
- All commands are interactive elements

### Basic
- **~play**                      
    - Displays the song selection interface to the sender
- **~queue**                     
    - Show current queue, including currently playing
- **~balance**                   
    - Show user balance
- **~earn**                      
    - Display ways to earn virtual money
- **~coin**                      
    - Coin flip game
- **~21**                        
    - Blackjack/21 game
- **~send-money**
    - Send money (also used for payments)
- **~loan**
    - Request to borrow money

### Bronze
- **~skip**                      
    - Skip the current song

### Silver
- **~skip**                      
    - Skip the current song
- **~queue**                     
    - Additional permission to move songs around in the queue
- **~download <song name>**      
    - Downloads the song from YouTube

### Gold
- **~skip**                      
    - Skip the current song
- **~queue**                     
    - Additional permission to move songs around in the queue
- **~download <song name>**      
    - Downloads the song from YouTube
- **~upload <attached_file>**    
    - Upload a song
- **~stop**                      
    - Stop music and clear queue (tbd the level needed, might be basic)
- **~send**                      
    - Sends a song to the user in a hidden message for them to download
- **FEATURE**                    
    - All prices are 25% (difference is paid by the treasury)


## 21 / Blackjack

### Overview
- **Interactive Window**
- **Hidden from Others**

### Limits
- **Basic**                     
    - 25 cent limit per bet
- **Bronze**                    
    - 1 dollar limit per bet
- **Silver**                    
    - 5 dollar limit per bet
- **Gold**                      
    - No limits

## Money System Overview

### Treasury
- **Subsidies**
    - 1 cent, per user, per day

- **Role Sale**
    - **Basic**
        - Free, given to everyone
    - **Bronze**
        - Cost: $3.00
    - **Silver**
        - Cost: $10.00
    - **Gold**
        - Cost: $50.00

- **Lending**
    - **Basic**
        - Limit: $1.00
        - Interest Rate: 10% / Day
    - **Bronze**
        - Limit: $5.00
        - Interest Rate: 5% / Week
    - **Silver**
        - Limit: $25.00
        - Interest Rate: 2% / Month
    - **Gold**
        - Limit: $100.00
        - Interest Rate: 0.5% / Month

### Administrative Commands
- **~stop**                
    - Clear the song queue
- **~unplug**
    - Similar to `~stop` but also effectively shuts down the jukebox, to prevent use.
