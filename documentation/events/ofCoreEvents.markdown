#class ofCoreEvents


<!--
_visible: True_
_advanced: False_
_istemplated: False_
_extends: _
-->

##InlineDescription






##Description

Class for the core events in oF. This is used inside oF to create the global var ofEvents that can be used to register any class to the core events setup, update, draw, exit, keyPressed, keyReleased, mousePressed, mouseReleased, mouseDragged, mouseMoved and windowResize.

To do so use the functions ofAddListener and ofRemoveListener.

For a complete example take a look at the advancedEventsExample





##Methods



###void disable()

<!--
_syntax: disable()_
_name: disable_
_returns: void_
_returns_description: _
_parameters: _
_access: public_
_version_started: 006_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###void enable()

<!--
_syntax: enable()_
_name: enable_
_returns: void_
_returns_description: _
_parameters: _
_access: public_
_version_started: 006_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###uint64_t getFrameNum()

<!--
_syntax: getFrameNum()_
_name: getFrameNum_
_returns: uint64_t_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###float getFrameRate()

<!--
_syntax: getFrameRate()_
_name: getFrameRate_
_returns: float_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool getKeyPressed(key)

<!--
_syntax: getKeyPressed(key)_
_name: getKeyPressed_
_returns: bool_
_returns_description: _
_parameters: int key_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###double getLastFrameTime()

<!--
_syntax: getLastFrameTime()_
_name: getLastFrameTime_
_returns: double_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###int getModifiers()

<!--
_syntax: getModifiers()_
_name: getModifiers_
_returns: int_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool getMousePressed(button)

<!--
_syntax: getMousePressed(button)_
_name: getMousePressed_
_returns: bool_
_returns_description: _
_parameters: int button_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###int getMouseX()

<!--
_syntax: getMouseX()_
_name: getMouseX_
_returns: int_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###int getMouseY()

<!--
_syntax: getMouseY()_
_name: getMouseY_
_returns: int_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###int getPreviousMouseX()

<!--
_syntax: getPreviousMouseX()_
_name: getPreviousMouseX_
_returns: int_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###int getPreviousMouseY()

<!--
_syntax: getPreviousMouseY()_
_name: getPreviousMouseY_
_returns: int_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###float getTargetFrameRate()

<!--
_syntax: getTargetFrameRate()_
_name: getTargetFrameRate_
_returns: float_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyDragEvent(info)

<!--
_syntax: notifyDragEvent(info)_
_name: notifyDragEvent_
_returns: bool_
_returns_description: _
_parameters: ofDragInfo info_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyDraw()

<!--
_syntax: notifyDraw()_
_name: notifyDraw_
_returns: bool_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyExit()

<!--
_syntax: notifyExit()_
_name: notifyExit_
_returns: bool_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyKeyEvent(&keyEvent)

<!--
_syntax: notifyKeyEvent(&keyEvent)_
_name: notifyKeyEvent_
_returns: bool_
_returns_description: _
_parameters: ofKeyEventArgs &keyEvent_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyKeyPressed(key, keycode, scancode, codepoint)

<!--
_syntax: notifyKeyPressed(key, keycode, scancode, codepoint)_
_name: notifyKeyPressed_
_returns: bool_
_returns_description: _
_parameters: int key, int keycode, int scancode, uint32_t codepoint_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyKeyReleased(key, keycode, scancode, codepoint)

<!--
_syntax: notifyKeyReleased(key, keycode, scancode, codepoint)_
_name: notifyKeyReleased_
_returns: bool_
_returns_description: _
_parameters: int key, int keycode, int scancode, uint32_t codepoint_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyMouseDragged(x, y, button)

<!--
_syntax: notifyMouseDragged(x, y, button)_
_name: notifyMouseDragged_
_returns: bool_
_returns_description: _
_parameters: int x, int y, int button_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyMouseEntered(x, y)

<!--
_syntax: notifyMouseEntered(x, y)_
_name: notifyMouseEntered_
_returns: bool_
_returns_description: _
_parameters: int x, int y_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyMouseEvent(&mouseEvent)

<!--
_syntax: notifyMouseEvent(&mouseEvent)_
_name: notifyMouseEvent_
_returns: bool_
_returns_description: _
_parameters: ofMouseEventArgs &mouseEvent_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyMouseExited(x, y)

<!--
_syntax: notifyMouseExited(x, y)_
_name: notifyMouseExited_
_returns: bool_
_returns_description: _
_parameters: int x, int y_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyMouseMoved(x, y)

<!--
_syntax: notifyMouseMoved(x, y)_
_name: notifyMouseMoved_
_returns: bool_
_returns_description: _
_parameters: int x, int y_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyMousePressed(x, y, button)

<!--
_syntax: notifyMousePressed(x, y, button)_
_name: notifyMousePressed_
_returns: bool_
_returns_description: _
_parameters: int x, int y, int button_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyMouseReleased(x, y, button)

<!--
_syntax: notifyMouseReleased(x, y, button)_
_name: notifyMouseReleased_
_returns: bool_
_returns_description: _
_parameters: int x, int y, int button_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyMouseScrolled(x, y, scrollX, scrollY)

<!--
_syntax: notifyMouseScrolled(x, y, scrollX, scrollY)_
_name: notifyMouseScrolled_
_returns: bool_
_returns_description: _
_parameters: int x, int y, float scrollX, float scrollY_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifySetup()

<!--
_syntax: notifySetup()_
_name: notifySetup_
_returns: bool_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###void notifyTouchCancelled(x, y, touchID)

<!--
_syntax: notifyTouchCancelled(x, y, touchID)_
_name: notifyTouchCancelled_
_returns: void_
_returns_description: _
_parameters: int x, int y, int touchID_
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###void notifyTouchDoubleTap(x, y, touchID)

<!--
_syntax: notifyTouchDoubleTap(x, y, touchID)_
_name: notifyTouchDoubleTap_
_returns: void_
_returns_description: _
_parameters: int x, int y, int touchID_
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###void notifyTouchDown(x, y, touchID)

<!--
_syntax: notifyTouchDown(x, y, touchID)_
_name: notifyTouchDown_
_returns: void_
_returns_description: _
_parameters: int x, int y, int touchID_
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###void notifyTouchEvent(&touchEvent)

<!--
_syntax: notifyTouchEvent(&touchEvent)_
_name: notifyTouchEvent_
_returns: void_
_returns_description: _
_parameters: ofTouchEventArgs &touchEvent_
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###void notifyTouchMoved(x, y, touchID)

<!--
_syntax: notifyTouchMoved(x, y, touchID)_
_name: notifyTouchMoved_
_returns: void_
_returns_description: _
_parameters: int x, int y, int touchID_
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###void notifyTouchUp(x, y, touchID)

<!--
_syntax: notifyTouchUp(x, y, touchID)_
_name: notifyTouchUp_
_returns: void_
_returns_description: _
_parameters: int x, int y, int touchID_
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyUpdate()

<!--
_syntax: notifyUpdate()_
_name: notifyUpdate_
_returns: bool_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyWindowMoved(x, y)

<!--
_syntax: notifyWindowMoved(x, y)_
_name: notifyWindowMoved_
_returns: bool_
_returns_description: _
_parameters: int x, int y_
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool notifyWindowResized(width, height)

<!--
_syntax: notifyWindowResized(width, height)_
_name: notifyWindowResized_
_returns: bool_
_returns_description: _
_parameters: int width, int height_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

### ofCoreEvents()

<!--
_syntax: ofCoreEvents()_
_name: ofCoreEvents_
_returns: _
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###void setFrameRate(_targetRate)

<!--
_syntax: setFrameRate(_targetRate)_
_name: setFrameRate_
_returns: void_
_returns_description: _
_parameters: int _targetRate_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###void setTimeModeFiltered(alpha)

<!--
_syntax: setTimeModeFiltered(alpha)_
_name: setTimeModeFiltered_
_returns: void_
_returns_description: _
_parameters: float alpha_
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###void setTimeModeFixedRate(nanosecsPerFrame)

<!--
_syntax: setTimeModeFixedRate(nanosecsPerFrame)_
_name: setTimeModeFixedRate_
_returns: void_
_returns_description: _
_parameters: uint64_t nanosecsPerFrame_
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###void setTimeModeSystem()

<!--
_syntax: setTimeModeSystem()_
_name: setTimeModeSystem_
_returns: void_
_returns_description: _
_parameters: _
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

##Variables



###bool bFrameRateSet

<!--
_name: bFrameRateSet_
_type: bool_
_access: private_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###bool bPreMouseNotSet

<!--
_name: bPreMouseNotSet_
_type: bool_
_access: private_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###int charEvent

<!--
_name: charEvent_
_type: int_
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###int currentMouseX

<!--
_name: currentMouseX_
_type: int_
_access: private_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###int currentMouseY

<!--
_name: currentMouseY_
_type: int_
_access: private_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofEventArgs > draw

<!--
_name: draw_
_type: ofEvent< ofEventArgs >_
_access: public_
_version_started: 006_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofEventArgs > exit

<!--
_name: exit_
_type: ofEvent< ofEventArgs >_
_access: public_
_version_started: 006_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent fileDragEvent

<!--
_name: fileDragEvent_
_type: ofEvent_
_access: public_
_version_started: 0073_
_version_deprecated: _
_summary: _
_visible: True_
_constant: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###chrono::nanoseconds fixedRateTimeNanos

<!--
_name: fixedRateTimeNanos_
_type: chrono::nanoseconds_
_access: private_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofFpsCounter fps

<!--
_name: fps_
_type: ofFpsCounter_
_access: private_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofKeyEventArgs > keyPressed

<!--
_name: keyPressed_
_type: ofEvent< ofKeyEventArgs >_
_access: public_
_version_started: 006_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofKeyEventArgs > keyReleased

<!--
_name: keyReleased_
_type: ofEvent< ofKeyEventArgs >_
_access: public_
_version_started: 006_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent messageEvent

<!--
_name: messageEvent_
_type: ofEvent_
_access: public_
_version_started: 0073_
_version_deprecated: _
_summary: _
_visible: True_
_constant: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###int modifiers

<!--
_name: modifiers_
_type: int_
_access: private_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofMouseEventArgs > mouseDragged

<!--
_name: mouseDragged_
_type: ofEvent< ofMouseEventArgs >_
_access: public_
_version_started: 006_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofMouseEventArgs > mouseEntered

<!--
_name: mouseEntered_
_type: ofEvent< ofMouseEventArgs >_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofMouseEventArgs > mouseExited

<!--
_name: mouseExited_
_type: ofEvent< ofMouseEventArgs >_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofMouseEventArgs > mouseMoved

<!--
_name: mouseMoved_
_type: ofEvent< ofMouseEventArgs >_
_access: public_
_version_started: 006_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofMouseEventArgs > mousePressed

<!--
_name: mousePressed_
_type: ofEvent< ofMouseEventArgs >_
_access: public_
_version_started: 006_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofMouseEventArgs > mouseReleased

<!--
_name: mouseReleased_
_type: ofEvent< ofMouseEventArgs >_
_access: public_
_version_started: 006_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofMouseEventArgs > mouseScrolled

<!--
_name: mouseScrolled_
_type: ofEvent< ofMouseEventArgs >_
_access: public_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###set< int > pressedKeys

<!--
_name: pressedKeys_
_type: set< int >_
_access: private_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###set< int > pressedMouseButtons

<!--
_name: pressedMouseButtons_
_type: set< int >_
_access: private_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###int previousMouseX

<!--
_name: previousMouseX_
_type: int_
_access: private_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###int previousMouseY

<!--
_name: previousMouseY_
_type: int_
_access: private_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofEventArgs > setup

<!--
_name: setup_
_type: ofEvent< ofEventArgs >_
_access: public_
_version_started: 006_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###float targetRate

<!--
_name: targetRate_
_type: float_
_access: private_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###enum TimeMode timeMode

<!--
_name: timeMode_
_type: enum TimeMode_
_access: private_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofTimer timer

<!--
_name: timer_
_type: ofTimer_
_access: private_
_version_started: 0.9.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent touchCancelled

<!--
_name: touchCancelled_
_type: ofEvent_
_access: public_
_version_started: 0073_
_version_deprecated: _
_summary: _
_visible: True_
_constant: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent touchDoubleTap

<!--
_name: touchDoubleTap_
_type: ofEvent_
_access: public_
_version_started: 0073_
_version_deprecated: _
_summary: _
_visible: True_
_constant: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent touchDown

<!--
_name: touchDown_
_type: ofEvent_
_access: public_
_version_started: 0073_
_version_deprecated: _
_summary: _
_visible: True_
_constant: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent touchMoved

<!--
_name: touchMoved_
_type: ofEvent_
_access: public_
_version_started: 0073_
_version_deprecated: _
_summary: _
_visible: True_
_constant: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent touchUp

<!--
_name: touchUp_
_type: ofEvent_
_access: public_
_version_started: 0073_
_version_deprecated: _
_summary: _
_visible: True_
_constant: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofEventArgs > update

<!--
_name: update_
_type: ofEvent< ofEventArgs >_
_access: public_
_version_started: 006_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###int windowMoved

<!--
_name: windowMoved_
_type: int_
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofEvent< ofResizeEventArgs > windowResized

<!--
_name: windowResized_
_type: ofEvent< ofResizeEventArgs >_
_access: public_
_version_started: 006_
_version_deprecated: _
_summary: _
_visible: True_
_constant: False_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

