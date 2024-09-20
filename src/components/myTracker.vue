<!-- src/components/InitiativeTracker.vue -->
<template>
    <div class="container">
      <div class="panel">
        <div class="title">Characters  <NewPlayerIcon class="arrow"/></div>
        <div class="character">Player 1 <span class="bonus">+2</span></div>
        <div class="character">Player 2 <span class="bonus">+1</span></div>
        <div class="character">Player 3 <span class="bonus">+4</span></div>
      </div>
  
      <div class="action-buttons">
        <LeftArrowIcon class="arrow" /> 

 <!--        <button class="button">Roll Initiative</button>
        <button class="button">Add Character</button> -->
        <RightArrowIcon class="arrow" /> 

      </div>
  
      <div class="panel">
        <div class="title">Combatants  <DiceIcon class="arrow"/></div>
        <div class="character combatant">Player 4 <span class="bonus">18</span> <button class="remove">✖️</button></div>
        <div class="character combatant">Player 5 <span class="bonus">12</span> <button class="remove">✖️</button></div>
        <div class="character combatant">Player 6 <span class="bonus">12</span> <button class="remove">✖️</button></div>
      </div>
  
      <DownArrowIcon class="arrow"/>
    </div>
  </template>
  
  <!-- script section -->
<script setup lang="ts" >
import '../assets/myTracker.css';
import RightArrowIcon from '../assets/dot-arrow-right.svg';
import LeftArrowIcon from '../assets/dot-arrow-left.svg';
import DownArrowIcon from '../assets/fast-arrow-down.svg';
import currentPlayerIcon from '../assets/play-solid.svg'
import NewPlayerIcon from '../assets/user-plus.svg'
import DiceIcon from '../assets/hexagon-dice.svg'
 
</script>

  