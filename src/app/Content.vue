<script>
import users from '../mocks/users.json';
import UserCard from './UserCard.vue';
export default {
  data() {
    return {
      users,
    };
  },
  components: {
    UserCard,
  },
};
</script>

<template>
  <div class="main-content">
    <ul>
      <li v-for="user in users" :key="user.name">
        <UserCard :name="user.name" />
      </li>
    </ul>
  </div>
</template>

<style>
.main-content {
  min-height: calc(100vh - 6rem);
  background-color: darkgreen;
}
</style>
