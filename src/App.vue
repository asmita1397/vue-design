<template>
  <div id="app">
    <!-- <testControlContextMenu2 />
    <hr> -->
    <UseLabel />
    <hr />
     <UseCheckBox />
    <hr />
    <UseComboBox />
    <hr />
    <UseCommandButton />
    <hr />
    <UseFrame />
    <hr />
    
    <UseListBox />
    <hr />
    <UseMultiPage />
    <hr />
    <UseOptionButton />
    <hr />
    <UsePicture />
    <hr />
    
    <UseScroll />
    <hr />
    <UseSpinButton />
    <hr />
    <UseTabStrip />
    <hr />
    <UseTextBox />
    <hr />
    <UseToggleButton />
    <hr />
  <!--  <hr /> -->
    <!-- <testControlContextMenu4 />
    <hr>
    <testControlContextMenu3 />
    <hr> -->
    <!-- <ControlContextMenu />
    <hr /> 
    <UserformContextMenu />
    <hr> -->
    <!-- <tabOrderModal />
    <hr>
    <ErrorPopUp />-->
    <hr>
    <!-- <ToolBox /> 
    <hr> -->
    <!-- <UserFormDesign />
    <hr> -->
    <!-- <ColorPallate /> -->
    <!-- <testTabOrder /> -->
    <!-- <hr>
    <Pop-up-tutorial /> -->
    <div style="margin-bottom:100px"></div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import UseCheckBox from "./views/controls/UseCheckBox.vue";
import UseComboBox from "./views/controls/UseComboBox.vue";
import UseCommandButton from "./views/controls/UseCommandButton.vue";
import UseFrame from "./views/controls/UseFrame.vue";
import UseLabel from "./views/controls/UseLabel.vue";

import UseListBox from "./views/controls/UseListBox.vue";
import UseMultiPage from "./views/controls/UseMultiPage.vue";
import UseOptionButton from "./views/controls/UseOptionButton.vue";
import UsePicture from "./views/controls/UsePicture.vue";
import UseRefEdit from "./views/controls/UseRefEdit.vue";

import UseScroll from "./views/controls/UseScroll.vue";
import UseSpinButton from "./views/controls/UseSpinButton.vue";
import UseTabStrip from "./views/controls/UseTabStrip.vue";
import UseTextBox from "./views/controls/UseTextBox.vue";
import UseToggleButton from "./views/controls/UseToggleButton.vue";

import ControlContextMenu from "./views/contextMenu/ControlContextMenu.vue";
import UserformContextMenu from "./views/contextMenu/UserformContextMenu.vue";
import ErrorPopUp from './views/dialogs/ErrorPopUp.vue'
// import testControlContextMenu2 from "./views/test/testControlContextMenu2.vue";
import testTabOrder from './views/dialogs/testTabOrder.vue';
import testControlContextMenu3 from './views/test/testControlContextMenu3.vue';
// import testControlContextMenu4 from './views/test/testControlContextMenu4.vue';
import TabOrderModal from './views/dialogs/TabOrderModal.vue'
import PopUpTutorial from './views/dialogs/Pop-up-tutorial.vue'
import ColorPallate from './table-design/ColorPallate.vue'
import ToolBox from './views/dialogs/ToolBox.vue'
import UserFormDesign from './views/dialogs/UserFormDesign.vue'

@Component({
  components: {
    UseCheckBox,
    UseComboBox,
    UseCommandButton,
    UseFrame,
    UseLabel,
    UseListBox,
    UseMultiPage,
    UseOptionButton,
    UsePicture,
    UseRefEdit,
    UseScroll,
    UseSpinButton,
    UseTabStrip,
    UseTextBox,
    UseToggleButton,
    ControlContextMenu,
    UserformContextMenu,
    // testControlContextMenu2,
    testTabOrder,
    testControlContextMenu3,
    // testControlContextMenu4,
    TabOrderModal,
    ErrorPopUp,
    PopUpTutorial,
    ColorPallate,
    ToolBox,
    UserFormDesign
  }
})
export default class App extends Vue {}
</script>

<style scoped>
</style>
