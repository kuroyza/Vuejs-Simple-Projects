<template>

   <div class="projects">
      <h1>All Projects</h1>

      <ul class="projects__list">
         <li class="projects__list--item">
            <router-link to="/projects/dual-listbox">
            Dual Listbox
            </router-link>

         </li>
         <li class="projects__list--item">
            <router-link to="/projects/quotes-maker">
            Quotes Maker
            </router-link>
         </li>
         <li class="projects__list--item">
            <router-link to="/projects/card-matching">
            Card Matching
            </router-link>
         </li>
         <li class="projects__list--item">
            <router-link to="/projects/tic-tac-toe">
            Tic Tac Toe
            </router-link>
         </li>
         <li class="projects__list--item">
            <router-link to="/projects/highlighter">
            Highlighter
            </router-link>
         </li>
         <li class="projects__list--item">
            <router-link to="/projects/snake-game">
            Snake Game
            </router-link>
         </li>
      </ul>
   </div>
</template>


<style lang="scss" scoped>
   .projects__list{
      margin-top: 20px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;

      &--item{
         margin: 10px 0;
      }
   }

</style>