<template>

      <v-navigation-drawer
      >
      
        <v-list>
          <v-list-item
            prepend-avatar="Foto Hikmah.jpeg"
            subtitle="hikmahnurfauziah22@gmailcom"
            title="Hikmah Nur Fauziah"
          ></v-list-item>
        </v-list>


        <v-list density="compact" nav>
          <v-list-item prepend-icon="mdi-folder" title="Home" :to="'/home'" ></v-list-item>
          <v-list-item prepend-icon="mdi-account-multiple" title="Dosen" :to="'/dosen-entry'"></v-list-item>
          <v-list-item prepend-icon="mdi-star" title="Mahasiwa" :to="'/mahasiswa-entry'"></v-list-item>
          <v-list-item prepend-icon="mdi-star" title="Ruangan" :to="'/ruangan-entry'"></v-list-item>
        </v-list>
      </v-navigation-drawer>

      
</template>