<template>
  <div class="main">
    <!-- BEGIN: Top Bar -->
    <TopBar />
    <!-- END: Top Bar -->

    <!-- BEGIN: Invite Friends Modal -->
    <InviteFriendsModel />
    <!-- END: Invite Friends Modal -->

    <!-- BEGIN: Side Menu -->
    <SideMenu @showSideBar="setSideBarOptionValue" />

    <div class="md:pl-16 pt-16">
      <div
        class="-mt-16 ml-auto xl:-ml-16 mr-auto xl:pl-16 pt-16 xl:h-screen w-auto sm:w-3/5 xl:w-auto grid grid-cols-12 gap-6"
      >
        <!-- BEGIN: Side Content Profile -->
        <SideContentProfile v-if="openedSideBarOption === 'profile'" />
        <!-- END: Side Content Profile -->

        <!-- BEGIN: Side Content Contacts -->
        <SideContentContacts v-if="openedSideBarOption === 'contact'" />
        <!-- END: Side Content Contacts -->

        <!-- BEGIN: Side Content Chats -->
        <SideContentChats v-if="openedSideBarOption === 'chat'" />
        <!-- END: Side Content Chats -->

        <!-- BEGIN: Side Content Groups -->
        <SideContentGroups v-if="openedSideBarOption === 'group'" />
        <!-- END: Side Content Groups -->

        <!-- BEGIN: Chat Box -->
        <ChatBox />
        <!-- END: Chat Box -->

        <!-- BEGIN: Right Content Info -->
        <RightContentInfo />
        <!-- END: Right Content Info -->
      </div>
    </div>
    <!-- END: Side Menu -->
  </div>
</template>

<script setup>
import { ref } from "vue";
import TopBar from "@/components/TopSonChat/Top_bar.vue";
import InviteFriendsModel from "@/components/TopSonChat/Invite_friends_model.vue";
import SideMenu from "@/components/TopSonChat/Side_menu.vue";
import SideContentProfile from "@/components/TopSonChat/Side_Content/Profile.vue";
import SideContentContacts from "@/components/TopSonChat/Side_Content/Contacts.vue";
import SideContentChats from "@/components/TopSonChat/Side_Content/Chats.vue";
import SideContentGroups from "@/components/TopSonChat/Side_Content/Groups.vue";
import ChatBox from "@/components/TopSonChat/Chat_box.vue";
import RightContentInfo from "@/components/TopSonChat/Right_content_info.vue";
let openedSideBarOption = ref("chat");
function setSideBarOptionValue(value) {
  console.log("in the setsidebar");
  openedSideBarOption.value = value;
  console.log(value);
  console.log(openedSideBarOption.value);
}
</script>

