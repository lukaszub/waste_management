<template>
  

  
  <h1 class="text-3xl font-bold dark:text-white text-center my-5">Formularz Reklamacji - odpady stałe</h1>

  <form class="max-w-sm mx-auto pt-5">
  <div class="mb-5">
    <label for="text" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Adres:</label>
    <input type="text" id="adress" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500 dark:shadow-sm-light" placeholder="Miejscowość, ul. Nazwa Ulicy, numer budynku" required>
  </div>
  <div class="mb-5">
    <label for="numer" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Telefon Kontaktowy:</label>
    <input type="number" id="phone_number" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500 dark:shadow-sm-light" required>
  </div>
  <div class="mb-5">
    <label for="date" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Data braku odbioru:</label>
    <input type="date" id="date_of_complain" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500 dark:shadow-sm-light" required>
  </div>
  <div class="mb-5">
    <label for="text" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Frakcja:</label>
    <input type="text" id="type_of_garbage" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500 dark:shadow-sm-light" placeholder="zmieszane, plastik, papier itp" required>
  </div>
  <div class="mb-5">
    <label for="date" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Zaplanowana data odbioru:</label>
    <input type="date" id="date_of_complain" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500 dark:shadow-sm-light" required>
  </div>

  <div class="mb-5">
    <label for="status" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Status</label>
    <select id="status" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
      <option selected>Choose a country</option>
      <option value="accepted">Akceptacja</option>
      <option value="decline">Odrzucone</option>
      <option value="other">Inne</option>
    </select>
  </div>

  <button type="submit" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Register new account</button>
</form>


</template>

<script>
import MainLayout from '../../Layouts/MainLayout.vue'
export default {
  layout: MainLayout
}
</script>
